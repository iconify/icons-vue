<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rn7je3bil"/><path class="a9429mbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-san" /></template>
<style>
.a9429mbjd {
  fill: var(--svg-color--a1e0ff, #a1e0ff);
  d: path("M30 13.992L2 8.721V2l28 5.271Zm0 10.579L2 19.3v-6.72l28 5.27Z");
}

.rn7je3bil {
  fill: var(--svg-color--295892, #295892);
  d: path("M30 17.832L2 23.28V30l28-5.447Zm0-10.579L2 12.7v6.72l28-5.447Z");
}

</style>
