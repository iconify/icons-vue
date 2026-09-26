<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2lw1wbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-neutral-sharp-fill" /></template>
<style>
.j2lw1wbru {
  fill: currentColor;
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12ZM10 9L8 9L8 12L10 12L10 9ZM16 9L14 9L14 12L16 12L16 9ZM8 15L8 17L16 17L16 15L8 15Z");
}

</style>
