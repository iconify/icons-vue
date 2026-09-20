<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3529i0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contextual-token-add-sharp" /></template>
<style>
.bd3529i0t {
  fill: currentColor;
  d: path("M18 9V7h-2V6h2V4h1v2h2v1h-2v2zM6.77 15.346h5.73v-1.961H6.77zm0-4.73h5.73V8.654H6.77zM3 19V5h10.867q-.123.354-.187.733t-.064.767q0 1.1.445 2.026t1.208 1.59v5.23h1.962v-4.138q.307.088.622.133q.314.044.647.044q.699 0 1.325-.186T21 10.692V19z");
}

</style>
