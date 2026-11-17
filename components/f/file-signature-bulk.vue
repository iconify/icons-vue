<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vn5g6zbpx"/><path class="i1l-ezbwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-signature-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i1l-ezbwp {
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3V3a1 1 0 0 1 1.698-.716l.009.008v.001ZM15 8h1.586L14 5.414V7a.997.997 0 0 0 1 1m-2.031 5.999h.009q.038-.013.075-.032c.137-.069.265-.159.392-.243c.473-.316.967-.613 1.555-.613c.921.001 1.511.675 1.894 1.442a1 1 0 1 1-1.788.894a2 2 0 0 0-.174-.295c-.131.069-.254.154-.377.236c-.473.315-.967.612-1.555.612c-.51 0-.995-.173-1.373-.518a2.7 2.7 0 0 1-.389-.45c-.203-.287-.369-.598-.573-.883a3.6 3.6 0 0 0-.372-.442c-.13-.129-.274-.263-.444-.338c-.03-.013-.072-.032-.106-.024c-.105.026-.194.125-.265.2c-.245.261-.424.584-.584.902a1 1 0 1 1-1.788-.894c.246-.493.536-.976.916-1.379c.337-.358.753-.648 1.235-.769c.959-.239 1.788.226 2.45.888c.38.38.682.817.963 1.271q.222.36.299.435M15 17a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

.vn5g6zbpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Z");
}

</style>
