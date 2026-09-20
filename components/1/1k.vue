<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jls_-szxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:1k" /></template>
<style>
.jls_-szxn {
  fill: currentColor;
  d: path("M12.539 14.692h.884v-2.365l2.289 2.365h1.211l-2.634-2.73l2.634-2.654H15.75l-2.327 2.326V9.308h-.885zm-3.731 0h.884V9.308H7.308v.884h1.5zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
