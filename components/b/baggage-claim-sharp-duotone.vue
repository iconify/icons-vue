<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x9d-0bqhe"/><path class="u7t-gdbnn"/><path clip-rule="evenodd" class="chzazobas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baggage-claim-sharp-duotone" /></template>
<style>
.chzazobas {
  fill-rule: evenodd;
  d: path("M14 7C14.552 7 15 7.448 15 8V11H16C16.552 11 17 11.448 17 12V16H7V12C7 11.448 7.448 11 8 11H9V8C9 7.448 9.448 7 10 7H14ZM11 9V11H13V9H11Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u7t-gdbnn {
  d: path("M6 17C7.657 17 9 18.343 9 20C9 21.657 7.657 23 6 23C4.343 23 3 21.657 3 20C3 18.343 4.343 17 6 17ZM18 17C19.657 17 21 18.343 21 20C21 21.657 19.657 23 18 23C16.343 23 15 21.657 15 20C15 18.343 16.343 17 18 17Z");
}

.x9d-0bqhe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 1V3.056L13.412 3.111C17.708 3.792 21 7.512 21 12V16H23V18H1V16H3V12C3 7.404 6.551 3.603 11 3.057V1H13Z");
}

</style>
