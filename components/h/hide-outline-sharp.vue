<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbtirkqik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hide-outline-sharp" /></template>
<style>
.zbtirkqik {
  fill: currentColor;
  d: path("M4.425 21L3 19.575L7.6 15H5v-2h6v6H9v-2.6zM13 11V5h2v2.6L19.575 3L21 4.425L16.4 9H19v2z");
}

</style>
