<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nlhfwhb-n"><path clip-rule="evenodd" class="op7nkib7n"/><path class="icnzvtbnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ftm" /></template>
<style>
.icnzvtbnb {
  d: path("M4.35 18.836V16.05h.9v2.34l2.25 1.161v1zm15.3-13.671V7.95h-.9V5.61L16.5 4.45v-1z");
}

.nlhfwhb-n {
  fill: var(--svg-color--26b6ea, #26b6ea);
}

.op7nkib7n {
  fill-rule: evenodd;
  d: path("M11.969 3L6.6 6.047v11.816L11.97 21l5.431-3.137V6.047zm.03.9L7.95 6.33L12 8.692l4.05-2.362zM7.5 7.05v4.05l3.6-2.016zm4.95 2.925v4.05l3.6-2.016zM16.5 7.05v4.05l-3.6-2.016zm-4.95 2.925v4.05l-3.6-2.016zM7.5 12.702V17.4l4.5 2.7l4.5-2.7v-4.698L12 15.15z");
}

</style>
