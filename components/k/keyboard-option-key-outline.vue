<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6r49jtdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-option-key-outline" /></template>
<style>
.z6r49jtdc {
  fill: currentColor;
  d: path("M14.775 19L7.85 7H3V5h6l6.925 12H21v2zM15 7V5h6v2z");
}

</style>
