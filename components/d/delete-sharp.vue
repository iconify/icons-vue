<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og4m9xb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:delete-sharp" /></template>
<style>
.og4m9xb8m {
  fill: currentColor;
  d: path("M9.808 17h1V8h-1zm3.384 0h1V8h-1zM6 20V6H5V5h4v-.77h6V5h4v1h-1v14z");
}

</style>
