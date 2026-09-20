<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqwmk1ogy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-business-sharp" /></template>
<style>
.uqwmk1ogy {
  fill: currentColor;
  d: path("M18 23v-3h-3v-2h3v-3h2v3h3v2h-3v3zM2 20v-6H1v-2l1-5h15l1 5v2h-1v3h-2v-3h-4v6zm2-2h5v-4H4zM2 6V4h15v2z");
}

</style>
