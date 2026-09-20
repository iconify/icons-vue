<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dzx-wp4mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:expand-up-left-20-filled" /></template>
<style>
.dzx-wp4mv {
  fill: currentColor;
  d: path("M14 4a2 2 0 0 1 2 2v4h-4a2 2 0 0 0-2 2v4H6a2 2 0 0 1-2-2v-2.5a.5.5 0 0 0-1 0V14a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3h-2.5a.5.5 0 0 0 0 1zm-5-.5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0V4.707l4.146 4.147a.5.5 0 1 0 .708-.708L4.707 4H8.5a.5.5 0 0 0 .5-.5");
}

</style>
