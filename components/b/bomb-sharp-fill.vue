<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xlv0wha8t"/><path class="kb0d0eb4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bomb-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kb0d0eb4s {
  d: path("M10.5858 10.5858L13.6568 7.5146L16.4854 10.3432L13.4142 13.4142M15.0711 8.9289L16.6874 7.3126L16.9803 7.0197M15.8507 4.1901L15.6521 3.4489L15.2639 2L15.0653 1.2588M19.2229 4.7771L19.5158 4.4842L20.5765 3.4235L20.8694 3.1306M19.8099 8.1493L20.5511 8.3479L22 8.7361L22.7412 8.9347");
}

.xlv0wha8t {
  fill: currentColor;
  d: path("M12.9497 20.9497C11.6841 22.2154 9.9327 23 8 23C4.134 23 1 19.866 1 16C1 12.134 4.134 9 8 9C11.866 9 15 12.134 15 16C15 17.9327 14.2154 19.6841 12.9497 20.9497Z");
  stroke: none;
}

</style>
