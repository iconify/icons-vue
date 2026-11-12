<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yvr49nc7e"/><path class="gswougl7d"/><path class="zj48ghuwd"/><path class="pq5xj2bli"/><path class="zfge7hb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-minimalistic-2-linear" /></template>
<style>
.gswougl7d {
  d: path("M14 16H10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pq5xj2bli {
  d: path("M12 21V22");
}

.yvr49nc7e {
  d: path("M19 8V15.8831C19 16.6438 18.6809 17.3697 18.1203 17.8841C14.6584 21.0607 9.3416 21.0607 5.87966 17.8841C5.31911 17.3697 5 16.6438 5 15.8831V8C5 6.11438 5 5.17157 5.58579 4.58579C6.17157 4 7.11438 4 9 4H15C16.8856 4 17.8284 4 18.4142 4.58579C19 5.17157 19 6.11438 19 8Z");
}

.zfge7hb-h {
  d: path("M14 4C14 2.89543 13.1046 2 12 2C10.8954 2 10 2.89543 10 4");
}

.zj48ghuwd {
  d: path("M14 10.9165C14 12.0671 13.1046 12.9999 12 12.9999C10.8954 12.9999 10 12.0671 10 10.9165C10 10.1966 10.783 9.23576 11.3691 8.6173C11.7161 8.25118 12.2839 8.25118 12.6309 8.6173C13.217 9.23576 14 10.1966 14 10.9165Z");
}

</style>
