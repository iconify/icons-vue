<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro9fgqbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-work-outline" /></template>
<style>
.ro9fgqbgl {
  fill: currentColor;
  d: path("M17 9h2V7h-2zm0 4h2v-2h-2zm0 4h2v-2h-2zm0 4v-2h4V5h-9v1.4l-2-1.45V3h13v18zM1 21V11l7-5l7 5v10H9v-5H7v5zm2-2h2v-5h6v5h2v-7L8 8.45L3 12zm8 0v-5H5v5v-5h6z");
}

</style>
