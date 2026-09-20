<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko9t8y8rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-all" /></template>
<style>
.ko9t8y8rs {
  fill: currentColor;
  d: path("M13 21v-8h8v8zm0-10V3h8v8zM3 11V3h8v8zm0 10v-8h8v8z");
}

</style>
