<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw981brth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-sort" /></template>
<style>
.tw981brth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.94 10.304L10.94 5.304C11.5885 4.8987 12.4115 4.8987 13.06 5.304L21.06 10.304C22.3134 11.0873 22.3134 12.9127 21.06 13.696L13.06 18.696C12.4115 19.1013 11.5885 19.1013 10.94 18.696L2.94 13.696C1.6866 12.9127 1.6866 11.0873 2.94 10.304ZM2 12L22 12");
}

</style>
