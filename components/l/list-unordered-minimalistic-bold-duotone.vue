<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="wi6ztdb2m"/><path class="v_bod2bfm"/><path class="ocwhqobpb"/></g><path class="cfhop_b-d"/><path class="r-trhqh5j"/><path class="ussnf-_yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-unordered-minimalistic-bold-duotone" /></template>
<style>
.cfhop_b-d {
  fill: currentColor;
  d: path("M5 5.25C5.41421 5.25 5.75 5.58579 5.75 6C5.75 6.41421 5.41421 6.75 5 6.75C4.58579 6.75 4.25 6.41421 4.25 6C4.25 5.58579 4.58579 5.25 5 5.25Z");
}

.ocwhqobpb {
  d: path("M20 15.25C20.4142 15.25 20.75 15.5858 20.75 16C20.75 16.4142 20.4142 16.75 20 16.75H10C9.58579 16.75 9.25 16.4142 9.25 16C9.25 15.5858 9.58579 15.25 10 15.25H20Z");
}

.r-trhqh5j {
  fill: currentColor;
  d: path("M5 10.25C5.41421 10.25 5.75 10.5858 5.75 11C5.75 11.4142 5.41421 11.75 5 11.75C4.58579 11.75 4.25 11.4142 4.25 11C4.25 10.5858 4.58579 10.25 5 10.25Z");
}

.ussnf-_yh {
  fill: currentColor;
  d: path("M5 15.25C5.41421 15.25 5.75 15.5858 5.75 16C5.75 16.4142 5.41421 16.75 5 16.75C4.58579 16.75 4.25 16.4142 4.25 16C4.25 15.5858 4.58579 15.25 5 15.25Z");
}

.v_bod2bfm {
  d: path("M20 10.25C20.4142 10.25 20.75 10.5858 20.75 11C20.75 11.4142 20.4142 11.75 20 11.75H10C9.58579 11.75 9.25 11.4142 9.25 11C9.25 10.5858 9.58579 10.25 10 10.25H20Z");
}

.wi6ztdb2m {
  d: path("M20 5.25C20.4142 5.25 20.75 5.58579 20.75 6C20.75 6.41421 20.4142 6.75 20 6.75H10C9.58579 6.75 9.25 6.41421 9.25 6C9.25 5.58579 9.58579 5.25 10 5.25H20Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
