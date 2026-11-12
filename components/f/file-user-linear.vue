<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zr35ecbmr"/><path class="e0cmz0boh"/><circle class="tvwvv6hyt"/><path class="vve12wqxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-user-linear" /></template>
<style>
.e0cmz0boh {
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tvwvv6hyt {
  cx: 9.25px;
  cy: 12.592px;
  r: 1.375px;
}

.vve12wqxb {
  d: path("M12.0001 16.7167C12.0001 17.476 12.0001 18.0916 9.25029 18.0916C6.50049 18.0916 6.50049 17.476 6.50049 16.7167C6.50049 15.9574 7.73162 15.3418 9.25029 15.3418C10.769 15.3418 12.0001 15.9574 12.0001 16.7167Z");
}

.zr35ecbmr {
  stroke-linejoin: round;
  d: path("M3.17139 3.17157C4.34296 2 6.23851 2 10.0296 2C11.5546 2 12.3173 2.00011 13.0093 2.26562C13.7012 2.53114 14.2651 3.03857 15.3929 4.05365L19.3516 7.61621C20.6558 8.78998 21.3078 9.3774 21.6538 10.1543C21.9998 10.9312 22 11.8079 22 13.5625V14C22 17.7712 22 19.6566 20.8284 20.8281C19.6569 21.9997 17.7712 22 14 22L9.9969 21.9997C6.22761 21.9997 4.34284 21.9997 3.17157 20.8284C2 19.6569 2 17.7712 2 14V9.9982C2 6.22817 2 4.34296 3.17139 3.17157Z");
}

</style>
