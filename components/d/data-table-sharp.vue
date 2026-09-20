<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuc7o3bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-table-sharp" /></template>
<style>
.uuc7o3bsz {
  fill: currentColor;
  d: path("M4 8.923h16V4.769H4zm0 5.154h16V9.923H4zm0 5.154h16v-4.154H4zM5.77 7.654V6.039h1.615v1.615zm0 5.154v-1.616h1.615v1.616zm0 5.154v-1.616h1.615v1.616z");
}

</style>
