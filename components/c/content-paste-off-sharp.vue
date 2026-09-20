<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ovdcv-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-off-sharp" /></template>
<style>
.g1ovdcv-o {
  fill: currentColor;
  d: path("m20 17.189l-1-1V5h-3v2.23h-5.958L6.812 4h3.44q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985H20zM12.578 5q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23m4.995 14L5 6.427V19zM4 20V5.427l-1.26-1.26l.714-.713l17.092 17.092l-.713.714l-1.26-1.26z");
}

</style>
