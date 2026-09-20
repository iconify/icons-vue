<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shdrzpbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-outline-sharp" /></template>
<style>
.shdrzpbdc {
  fill: currentColor;
  d: path("M5 19h1.098L16.796 8.302l-1.098-1.098L5 17.902zm-1 1v-2.52l13.875-13.9l2.54 2.563L6.52 20zM19 6.112L17.889 5zm-2.762 1.65l-.54-.558l1.098 1.098z");
}

</style>
