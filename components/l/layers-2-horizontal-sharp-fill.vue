<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gifme2b2g"/><path class="rblum1b7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-2-horizontal-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gifme2b2g {
  d: path("M7.501 1C7.865 1 8.202 1.199 8.377 1.519L10.86 6.032L8.372 10.556C7.878 11.455 7.878 12.546 8.372 13.445L10.86 17.968L8.377 22.481C8.202 22.801 7.865 23 7.501 23C7.137 23 6.801 22.801 6.625 22.481L1.125 12.481C0.96 12.182 0.96 11.818 1.125 11.519L6.625 1.519L6.698 1.404C6.885 1.153 7.182 1 7.501 1Z");
}

.rblum1b7b {
  d: path("M16.5 1C16.865 1 17.2 1.199 17.376 1.519L22.876 11.519C23.041 11.818 23.041 12.182 22.876 12.481L17.376 22.481C17.2 22.801 16.865 23 16.5 23C16.136 23 15.8 22.801 15.624 22.481L10.124 12.481C9.959 12.182 9.959 11.818 10.124 11.519L15.624 1.519L15.697 1.404C15.884 1.152 16.181 1 16.5 1Z");
}

</style>
