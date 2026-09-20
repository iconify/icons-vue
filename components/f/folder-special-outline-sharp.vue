<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k56fymbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-special-outline-sharp" /></template>
<style>
.k56fymbqo {
  fill: currentColor;
  d: path("m12.6 16.7l2.3-1.75l2.3 1.75l-.85-2.85l2.3-1.85H15.8l-.9-2.8L14 12h-2.85l2.3 1.85zM2 20V4h8l2 2h10v14zm2-2h16V8h-8.825l-2-2H4zm0 0V6z");
}

</style>
