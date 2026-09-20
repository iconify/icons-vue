<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku0eoab9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-square-sharp" /></template>
<style>
.ku0eoab9h {
  fill: currentColor;
  d: path("M11 17.5V13H2v-2h9V6.5h11v11z");
}

</style>
