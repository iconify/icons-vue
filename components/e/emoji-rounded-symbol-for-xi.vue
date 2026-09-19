<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iseamy5hy"/><path class="ab_ojbmsx"/><path class="k-ox03dns"/><path class="q7ogez4ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-rounded-symbol-for-xi" /></template>
<style>
.ab_ojbmsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.857 7.491C8.74 10.956 4.157 21.156 7.622 30.274a17.66 17.66 0 0 0 10.235 10.235M30.143 7.491c9.118 3.465 13.7 13.665 10.235 22.783a17.66 17.66 0 0 1-10.235 10.235M14.786 21.696v4.607m18.428-4.607v4.607");
}

.iseamy5hy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 10.946v10.75m0 4.608v10.75m-6.143-22.268h12.286m-12.286 3.071h12.286M17.857 30.143h12.286m-12.286 3.071h12.286M17.857 7.491v14.206h-7.525a13.82 13.82 0 0 1 3.993-7.68v4.3m3.532 22.192V26.303h-7.525a13.82 13.82 0 0 0 3.993 7.68v-4.3M30.143 7.49v14.205h7.525a13.82 13.82 0 0 0-3.993-7.678v4.3m-3.532 22.19V26.304h7.525a13.82 13.82 0 0 1-3.993 7.68v-4.3");
}

.k-ox03dns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24c0 11.874 9.626 21.5 21.5 21.5S45.5 35.874 45.5 24S35.874 2.5 24 2.5S2.5 12.126 2.5 24");
}

.q7ogez4ju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.696 21.696h4.607v4.607h-4.607zm0 15.358h4.607v4.607h-4.607zm0-30.714h4.607v4.606h-4.607z");
}

</style>
