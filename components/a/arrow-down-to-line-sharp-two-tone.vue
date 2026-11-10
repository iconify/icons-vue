<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mlgdwna5q"/><path clip-rule="evenodd" class="lcjr14bqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-to-line-sharp-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lcjr14bqi {
  fill-rule: evenodd;
  d: path("M20 21V23H4V21H20Z");
}

.mlgdwna5q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.999 1V15.802L18.58 10.123L20.006 11.524L12.712 18.946C12.524 19.138 12.267 19.246 11.999 19.246C11.731 19.246 11.474 19.138 11.286 18.946L3.992 11.524L5.418 10.123L10.999 15.802V1H12.999Z");
}

</style>
