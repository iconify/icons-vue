<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzok-775k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-multiple-24-regular" /></template>
<style>
.rzok-775k {
  fill: currentColor;
  d: path("M18.49 10.008a3.25 3.25 0 0 1 1.507 2.742v3.5a5.75 5.75 0 0 1-5.75 5.75h-4.5a3.25 3.25 0 0 1-2.743-1.508q.12.008.244.008h7a4.25 4.25 0 0 0 4.25-4.25v-6q0-.122-.008-.242M10.75 1A4.25 4.25 0 0 1 15 5.25v1.838a3.25 3.25 0 0 1 2.5 3.162v6a3.25 3.25 0 0 1-3.25 3.25h-7A3.25 3.25 0 0 1 4 16.25v-6a3.25 3.25 0 0 1 2.5-3.162V5.25A4.25 4.25 0 0 1 10.75 1m-3.5 7.5a1.75 1.75 0 0 0-1.75 1.75v6c0 .966.784 1.75 1.75 1.75h7A1.75 1.75 0 0 0 16 16.25v-6a1.75 1.75 0 0 0-1.75-1.75zm3.5 3.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m0-9.5A2.75 2.75 0 0 0 8 5.25V7h5.5V5.25a2.75 2.75 0 0 0-2.75-2.75");
}

</style>
