<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wx_-r42nx"/><path class="a26cjoroh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-duotone-sharp" /></template>
<style>
.a26cjoroh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21V11l4-4l4 4v10m-8-8l-4 2v6h16v-6l-4-2M12 3v4m-2-2h4");
}

.ft5dv1b6b {
  fill: none;
}

.wx_-r42nx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 15c0-.379.214-.725.553-.894L7 12.382V11c0-.265.105-.52.293-.707l4-4a.997.997 0 0 1 1.414 0l4 4A1 1 0 0 1 17 11v1.382l3.447 1.724A1 1 0 0 1 21 15v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
