<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b5cbgigwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-48-filled" /></template>
<style>
.b5cbgigwp {
  fill: currentColor;
  d: path("M24 9c-6.29 0-11.45 4.84-11.959 11H11.5a8.5 8.5 0 0 0 0 17h25a8.5 8.5 0 0 0 0-17h-.541C35.45 13.84 30.29 9 24 9");
}

</style>
