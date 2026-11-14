<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cpi8nib0w"/><path class="ixv163bsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-clubhouse" /></template>
<style>
.cpi8nib0w {
  d: path("m4.363 12.493l6.75-3.971a1.75 1.75 0 0 1 1.774 0l6.75 3.971a1.75 1.75 0 0 1 .863 1.508v5.249A1.75 1.75 0 0 1 18.75 21H5.25a1.75 1.75 0 0 1-1.75-1.75v-5.249a1.75 1.75 0 0 1 .863-1.508M12 8V2.5m1.652.578l.848.297a.927.927 0 0 1 0 1.75l-.848.297A1.242 1.242 0 0 1 12 4.25a1.242 1.242 0 0 1 1.652-1.172");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixv163bsh {
  d: path("M10 21v-4h4v4");
}

</style>
