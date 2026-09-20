<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq_iu57pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dynamic-form-sharp" /></template>
<style>
.zq_iu57pt {
  fill: currentColor;
  d: path("M2 11V4h11v7zm0 9v-7h13v7zm15 0v-9h-2V4h7l-2 5h2zM4.75 17.25h1.5v-1.5h-1.5zm0-9h1.5v-1.5h-1.5z");
}

</style>
