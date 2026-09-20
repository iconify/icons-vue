<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8b8sj4as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-copy-sharp" /></template>
<style>
.z8b8sj4as {
  fill: currentColor;
  d: path("M1 21V6h2v13h17v2zm4-4V2h7l2 2h9v13z");
}

</style>
