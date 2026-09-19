<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qx3179b1n"/><path class="g2wj9jbhp"/><path class="gu2w_0jia"/><path class="rnk89x9ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbl-icash" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.gu2w_0jia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.107 17.559c.407 3.193-5.073 7.342-6.107 9.208v4.54c-3.705-3.238-11.953-5.8-6.434-13.538L24 8.99l6.434 8.78c5.519 7.738-2.729 10.3-6.434 13.537");
}

.qx3179b1n {
  fill: currentColor;
  d: path("M15.093 33.991a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.rnk89x9ca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.893 17.559c-.407 3.193 5.073 7.342 6.107 9.208m7.116 7.043v5.83m0-2.405c0-.805.625-1.458 1.395-1.458h0c.771 0 1.396.653 1.396 1.458v2.405m-19.564-3.863v3.863m12.476-.326c.254.224.53.326 1.148.326h.313c.51 0 .922-.432.922-.966h0c0-.533-.413-.965-.922-.965h-.627c-.51 0-.922-.433-.922-.966h0c0-.534.413-.966.922-.966h.314c.617 0 .893.102 1.147.326m-9.001 1.582v.024c0 1.066-.828 1.931-1.85 1.931h0c-1.021 0-1.849-.865-1.849-1.931V35.74c0-1.067.828-1.932 1.85-1.932h0c1.02 0 1.849.865 1.849 1.932v.023m4.704 2.419c0 .805-.625 1.458-1.395 1.458h0c-.771 0-1.396-.653-1.396-1.458v-.947c0-.805.625-1.458 1.396-1.458h0c.77 0 1.395.653 1.395 1.458m0 2.405v-3.863");
}

</style>
