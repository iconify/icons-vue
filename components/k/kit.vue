<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d785swbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kit" /></template>
<style>
.d785swbja {
  fill: var(--svg-color--6025e1, #6025e1);
  fill-rule: evenodd;
  d: path("M5.118 5.43v13.029L9.458 21l9.425-4.553V7.48L9.898 3zm.164.064l4.071 2.821V20.81l.847-4.378l4.447-1.985v-4.87l-9.365-4.09z");
}

</style>
