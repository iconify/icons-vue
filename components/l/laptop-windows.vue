<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt2r9lvsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-windows" /></template>
<style>
.yt2r9lvsv {
  fill: currentColor;
  d: path("M1 18.77v-1h3.616V17q-.691 0-1.153-.462T3 15.385v-8.77q0-.69.463-1.152T4.615 5h14.77q.69 0 1.152.463T21 6.615v8.77q0 .69-.463 1.153T19.385 17v.77H23v1z");
}

</style>
