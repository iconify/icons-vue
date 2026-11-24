<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c-_3_02jc"/><path class="w3nq-7btj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circus-tent-bulk-sharp" /></template>
<style>
.c-_3_02jc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 21V11c.001-1.066.797-1.736 1.687-2.165c.85-.409 1.824-.666 2.73-.922c.784-.221 1.573-.439 2.333-.736c.525-.205 1.138-.48 1.543-.884a.997.997 0 0 1 1.414 0c.405.404 1.018.679 1.543.884c1.222.478 2.511.756 3.758 1.156c.443.143.885.3 1.305.502c.89.429 1.686 1.099 1.687 2.165v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.w3nq-7btj {
  d: path("M11 3a1.002 1.002 0 0 1 1.316-.949l3 1a1 1 0 0 1 0 1.898L13 5.721V7a1 1 0 0 1-2 0Zm5 10.237a3.003 3.003 0 0 1-4 0a3.003 3.003 0 0 1-4 0A3.001 3.001 0 0 1 3 11a1 1 0 0 1 2 0a1.002 1.002 0 0 0 1.707.707A1 1 0 0 0 7 11a1 1 0 0 1 2 0a1.002 1.002 0 0 0 1.707.707A1 1 0 0 0 11 11a1 1 0 0 1 2 0a1.002 1.002 0 0 0 1.707.707A1 1 0 0 0 15 11a1 1 0 0 1 2 0a1.002 1.002 0 0 0 1.707.707A1 1 0 0 0 19 11a1 1 0 0 1 2 0a3 3 0 0 1-5 2.237m-8.707 7.056l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414L12 18.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414");
}

</style>
