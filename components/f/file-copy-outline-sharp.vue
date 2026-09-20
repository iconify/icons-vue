<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx_hffbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-copy-outline-sharp" /></template>
<style>
.tx_hffbgl {
  fill: currentColor;
  d: path("M6 19V1h9l6 6v12zm8-11V3H8v14h11V8zM2 23V7h2v14h11v2zM8 3v5zv14z");
}

</style>
