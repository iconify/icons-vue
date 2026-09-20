<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jqtlw2bfx"/><path class="owztpbvgt"/><path class="pljw99uts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:chart-increasing" /></template>
<style>
.jqtlw2bfx {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M31 2H5a3 3 0 0 0-3 3v26a3 3 0 0 0 3 3h26a3 3 0 0 0 3-3V5a3 3 0 0 0-3-3");
}

.owztpbvgt {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M31 1H5a4 4 0 0 0-4 4v26a4 4 0 0 0 4 4h26a4 4 0 0 0 4-4V5a4 4 0 0 0-4-4m0 2c1.103 0 2 .897 2 2v4h-6V3zm-4 16h6v6h-6zm0-2v-6h6v6zM25 3v6h-6V3zm-6 8h6v6h-6zm0 8h6v6h-6zM17 3v6h-6V3zm-6 8h6v6h-6zm0 8h6v6h-6zM3 5c0-1.103.897-2 2-2h4v6H3zm0 6h6v6H3zm0 8h6v6H3zm2 14c-1.103 0-2-.897-2-2v-4h6v6zm6 0v-6h6v6zm8 0v-6h6v6zm12 0h-4v-6h6v4c0 1.103-.897 2-2 2");
}

.pljw99uts {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M4.998 33a2 2 0 0 1-1.759-2.948l7-13a2 2 0 0 1 3.175-.466l6.076 6.076l9.738-18.59a2 2 0 0 1 3.543 1.857l-11 21a2 2 0 0 1-1.47 1.05a2.02 2.02 0 0 1-1.716-.563l-6.1-6.099l-5.724 10.631A2 2 0 0 1 4.998 33");
}

</style>
