<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mokdlxb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-flowers" /></template>
<style>
.mokdlxb0a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.25q-3.25 0-3.25 3.25q0 .5.077.923Q8.25 5.25 7.5 5.25q-3.25 0-3.25 3.25q0 2.607 2.091 3.123q-.591.816-.591 1.877q0 1.347.951 2.299q.952.952 2.299.952q1.312 0 2.25-.904V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.894q.803.644 2.25.644q3.25 0 3.25-3.25q0-1.173-.424-1.923Q19.75 11 19.75 8.5q0-3.25-3.25-3.25q-.75 0-1.327.173q.077-.423.077-.923q0-3.25-3.25-3.25m-.055 10.852q-.088-.185-.202-.358q.125.006.257.006l.084-.001q-.078.167-.139.353");
}

</style>
