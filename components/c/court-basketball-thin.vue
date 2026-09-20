<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sv5c9mbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:court-basketball-thin" /></template>
<style>
.sv5c9mbun {
  fill: currentColor;
  d: path("M224 52H32a12 12 0 0 0-12 12v128a12 12 0 0 0 12 12h192a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12m4 112h-12a36 36 0 0 1 0-72h12ZM28 92h12a36 36 0 0 1 0 72H28Zm0 100v-20h12a44 44 0 0 0 0-88H28V64a4 4 0 0 1 4-4h92v136H32a4 4 0 0 1-4-4m196 4h-92V60h92a4 4 0 0 1 4 4v20h-12a44 44 0 0 0 0 88h12v20a4 4 0 0 1-4 4");
}

</style>
