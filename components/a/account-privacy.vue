<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaxjo4tch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-privacy" /></template>
<style>
.uaxjo4tch {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m4.75 6.25q2.319 0 4.126.751q-.322.694-.368 1.663Q13 16.578 13 18.75v1q0 .812.3 1.5H4q-1.75 0-1.75-1.75q0-2.798 2.468-4.577q2.32-1.673 5.782-1.673m10.518 3.732q-.243-.242-.518-.404V16q0-1.036-.732-1.768T18 13.5q-2.5 0-2.5 2.5v.464q-1.25.518-1.25 2.286v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768M19 16.25h-2V16q0-1 1-1q.414 0 .707.293T19 16zm-3.25 2.5q0-1 1-1h2.5q1 0 1 1v1q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707zm3 .75q0-.254-.02-.5H17v.5z");
}

</style>
