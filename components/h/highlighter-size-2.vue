<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grmufdbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:highlighter-size-2" /></template>
<style>
.grmufdbxv {
  fill: currentColor;
  d: path("m7.05 19.05l-2.1-2.1q-.3-.3-.3-.712t.3-.713L15.525 4.95q.3-.3.713-.3t.712.3l2.1 2.125q.275.275.275.7t-.275.7L8.475 19.05q-.3.3-.712.3t-.713-.3");
}

</style>
