<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my6nazbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-italic" /></template>
<style>
.my6nazbxk {
  fill: currentColor;
  d: path("M5.789 18.25v-1.115h3.634l3.48-10.27H9.27V5.75h8.308v1.116h-3.52l-3.48 10.269h3.52v1.115z");
}

</style>
