<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkfe-932z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-fill" /></template>
<style>
.rkfe-932z {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-1-.999A3 3 0 0 1 19 22H5a3 3 0 0 1-2.975-2.611L10 11.414L8.586 10L2 16.586V5c0-.448.099-.889.292-1.293l-.999-1a.999.999 0 1 1 1.414-1.414M22 17.757L6.243 2H19a3 3 0 0 1 3 3ZM15.158 6.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558");
}

</style>
