<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg1rc4bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-photo-alternate-sharp" /></template>
<style>
.xg1rc4bob {
  fill: currentColor;
  d: path("M3 21V3h11q-.5.65-.75 1.425T13 6q0 2.075 1.463 3.538T18 11q.8 0 1.575-.25T21 10v11zm3-4h12l-3.75-5l-3 4L9 13zm11-8V7h-2V5h2V3h2v2h2v2h-2v2z");
}

</style>
