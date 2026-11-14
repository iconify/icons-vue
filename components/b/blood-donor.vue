<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chtiswh7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blood-donor" /></template>
<style>
.chtiswh7i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m16 12q0-1.853-3.186-5.494q-.032-.038-.07-.07q-.112-.099-.254-.146q-.141-.048-.29-.038t-.282.076q-.134.066-.232.178Q14.25 17.147 14.25 19q0 3.5 3.75 3.5t3.75-3.5M10.5 13.25q2.695 0 4.699 1.014Q13 17.158 13 19q0 1.248.568 2.25H4q-1.75 0-1.75-1.75q0-2.798 2.468-4.577q2.32-1.673 5.782-1.673m7.5 1.903q1.632 1.954 2.08 3.097h-4.16q.448-1.143 2.08-3.097M18 21q-1.779 0-2.151-1.25h4.302Q19.779 21 18 21");
}

</style>
