<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jlyultbfy"/><path class="ozvbkmb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jiaoguan12123" /></template>
<style>
.jlyultbfy {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.ozvbkmb5u {
  d: path("m21.6 21.05l2-1.1v8.1m2.75-5.4c0-1.6 1.5-2.9 3.2-2.6c1.1.2 2 1.2 2.1 2.3c0 .8-.2 1.7-.8 2.2c-1.1.9-4.5 3.5-4.5 3.5h5.3m2.75-.7c.6.5 1.1.7 2.5.7h.3c1.1 0 2-.9 2-2h0c0-1.1-.9-2-2-2m-2.8-3.4c.6-.5 1.2-.7 2.5-.7h.3c1.1 0 2 .9 2 2h0c0 1.1-.9 2-2 2m-1.5.1h1.5m-28.4-3l2-1.1v8.1m2.75-5.4c0-1.6 1.5-2.9 3.2-2.6c1.1.2 2 1.2 2.1 2.3c0 .8-.2 1.7-.8 2.2c-1.1.9-4.5 3.5-4.5 3.5h5.3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
