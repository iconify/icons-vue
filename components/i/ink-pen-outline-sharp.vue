<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhznvebhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-pen-outline-sharp" /></template>
<style>
.bhznvebhc {
  fill: currentColor;
  d: path("m11.98 11.248l.907.906l5.829-5.829l-.906-.906zM5.136 19h.906l6.113-6.113l-.906-.906l-6.113 6.113zm8.105-5.76l-2.326-2.346l4.79-4.79l-.821-.821l-5.34 5.34l-.708-.67l6.067-6.066l1.51 1.51l1.398-1.399l2.346 2.346zM6.463 20H4.135v-2.327l6.76-6.779l2.346 2.347z");
}

</style>
