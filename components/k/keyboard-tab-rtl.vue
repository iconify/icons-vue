<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crc7ay_4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-tab-rtl" /></template>
<style>
.crc7ay_4i {
  fill: currentColor;
  d: path("M4 18H2V6h2zm8 0l-6-6l6-6l1.4 1.4L9.825 11H22v2H9.825l3.6 3.6z");
}

</style>
