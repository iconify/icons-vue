<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nsn8ivtct"/><path class="vk0i69bgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nsn8ivtct {
  stroke-opacity: 0.4;
  d: path("M6 17h12");
}

.vk0i69bgi {
  d: path("M6 15c-4.622-1.734-2.894-8.645 2-8a4 4 0 1 1 8 0c4.894-.645 6.622 6.266 2 8v6H6z");
}

</style>
