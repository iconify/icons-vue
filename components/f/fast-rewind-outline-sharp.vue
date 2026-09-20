<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggg3fccdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fast-rewind-outline-sharp" /></template>
<style>
.ggg3fccdt {
  fill: currentColor;
  d: path("m21.5 18l-9-6l9-6zm-10 0l-9-6l9-6zm-2-3.75v-4.5L6.1 12zm10 0v-4.5L16.1 12z");
}

</style>
