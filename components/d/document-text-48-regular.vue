<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t_z16gbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-48-regular" /></template>
<style>
.t_z16gbus {
  fill: currentColor;
  d: path("M16.25 23a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zM15 30.25c0-.69.56-1.25 1.25-1.25h15.5a1.25 1.25 0 1 1 0 2.5h-15.5c-.69 0-1.25-.56-1.25-1.25M16.25 35a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zM8 8.25A4.25 4.25 0 0 1 12.25 4h13.336a2.25 2.25 0 0 1 1.59.659l12.165 12.164c.422.422.659.994.659 1.591V39.75A4.25 4.25 0 0 1 35.75 44h-23.5A4.25 4.25 0 0 1 8 39.75zm4.25-1.75a1.75 1.75 0 0 0-1.75 1.75v31.5c0 .967.784 1.75 1.75 1.75h23.5a1.75 1.75 0 0 0 1.75-1.75V19h-9.75A3.75 3.75 0 0 1 24 15.25V6.5zm15.5 10h7.732L26.5 7.518v7.732c0 .69.56 1.25 1.25 1.25");
}

</style>
