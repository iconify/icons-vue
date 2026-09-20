<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx5h6vmwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eject-sharp" /></template>
<style>
.xx5h6vmwk {
  fill: currentColor;
  d: path("M6.154 18.346v-.923h11.692v.923zm.158-3.692L12 6.154l5.689 8.5z");
}

</style>
