<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwl7tbl8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:last-page-outline" /></template>
<style>
.cwl7tbl8r {
  fill: currentColor;
  d: path("m7 17.308l-.708-.708l4.6-4.6l-4.6-4.6L7 6.692L12.308 12zm9.5.192v-11h1v11z");
}

</style>
