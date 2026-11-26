<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rr3bh6-os"/><path class="v-mvkilyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-sort-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rr3bh6-os {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.41 17.044L2.41 14.544C1.4708 13.957 1 12.9725 1 12C1 11.0275 1.4708 10.043 2.41 9.456L10.41 4.456C11.3828 3.848 12.6172 3.848 13.59 4.456L21.59 9.456C22.5292 10.043 23.0001 11.0275 23.0001 12C23.0001 12.9725 22.5292 13.957 21.59 14.544L13.59 19.544C12.6172 20.152 11.3828 20.152 10.41 19.544Z");
  stroke: none;
}

.v-mvkilyq {
  d: path("M2.94 10.304L10.94 5.304C11.5885 4.8987 12.4115 4.8987 13.06 5.304L21.06 10.304C22.3134 11.0873 22.3134 12.9127 21.06 13.696L13.06 18.696C12.4115 19.1013 11.5885 19.1013 10.94 18.696L2.94 13.696C1.6866 12.9127 1.6866 11.0873 2.94 10.304ZM2 12L22 12");
}

</style>
