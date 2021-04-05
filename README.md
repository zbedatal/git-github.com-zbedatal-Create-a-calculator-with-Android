<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:orientation="vertical">

  <TextView
      android:id="@+id/textView"
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      android:layout_weight="0.7"
      android:hint="0"
      android:textSize="36sp" />

  <LinearLayout
      android:id="@+id/TextViexResult"
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      android:layout_weight="1"
      android:onClick="FuncButton"
      android:orientation="horizontal">

    <Button
        android:id="@+id/button9"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:shadowColor="@color/teal_200"
        android:text="1"
        android:textColor="@color/black"
        android:textColorHighlight="@color/black"
        android:textColorHint="#FCFCFC"
        android:textColorLink="@color/black"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button11"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="2"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button12"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="3"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button10"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="x"
        android:textSize="36sp" />
  </LinearLayout>

  <LinearLayout
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      android:layout_weight="1"
      android:orientation="horizontal">

    <Button
        android:id="@+id/button21"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="4"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button18"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="5"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button19"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="6"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button20"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="/"
        android:textSize="36sp" />

  </LinearLayout>

  <LinearLayout
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      android:layout_weight="1"
      android:orientation="horizontal">

    <Button
        android:id="@+id/button30"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="7"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button31"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="8"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button32"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="9"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button33"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="+"
        android:textSize="36sp" />
  </LinearLayout>

  <LinearLayout
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      android:layout_weight="1"
      android:orientation="horizontal">

    <Button
        android:id="@+id/button34"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="-"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button35"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="="
        android:textSize="36sp" />

    <Button
        android:id="@+id/button36"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="%"
        android:textSize="36sp" />

    <Button
        android:id="@+id/button37"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="14px"
        android:layout_weight="1"
        android:background="#009688"
        android:text="abc"
        android:textSize="36sp" />
  </LinearLayout>

</LinearLayout>
