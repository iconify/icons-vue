<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9gwkkbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forum" /></template>
<style>
.i9gwkkbmp {
  fill: currentColor;
  d: path("M7.23 16.23q-.326 0-.547-.22q-.221-.222-.221-.549v-1h11.75l.634.635V6h1q.327 0 .548.221t.222.548v12.539l-3.078-3.077zm-3.845-.691V3.769q0-.327.22-.548Q3.828 3 4.155 3h11.923q.327 0 .548.221t.221.548v7.923q0 .327-.221.549q-.221.22-.548.22H6.462z");
}

</style>
