<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s_nwbn9it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-16-filled" /></template>
<style>
.s_nwbn9it {
  fill: currentColor;
  d: path("M3.501 2a1.5 1.5 0 0 0-1.5 1.5v6.997a1.5 1.5 0 0 0 1.5 1.5h2.5V13H4.495a.5.5 0 0 0 0 1H11.5a.5.5 0 1 0 0-1H10v-1.003h2.501a1.5 1.5 0 0 0 1.5-1.5V3.5a1.5 1.5 0 0 0-1.5-1.5zm5.5 9.997V13H7v-1.003z");
}

</style>
