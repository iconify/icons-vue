<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fspcj4gup"/><path class="oa6ed9-mr"/><path class="tbcegmb1y"/><path class="jnf_2db5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dinosaur-outline-bold" /></template>
<style>
.fspcj4gup {
  d: path("M4 19c0 -4 3 -6 7 -6q1.5 -6 6 -6c0 -2 2 -3 3 -2s0 3 -1 3c0 3 -2 6 -5 7 0 2 -1 4 -3 4Z");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.oa6ed9-mr {
  d: path("m4 19 -2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tbcegmb1y {
  d: path("M7 18v3");
}

</style>
