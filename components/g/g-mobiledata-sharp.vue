<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqq8h5bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:g-mobiledata-sharp" /></template>
<style>
.fqq8h5bkf {
  fill: currentColor;
  d: path("M7.5 16.616V7.385h7.692v1H8.5v7.23h6V12.5h-2.384v-1H15.5v5.116z");
}

</style>
