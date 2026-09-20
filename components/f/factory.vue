<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajl35wbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:factory" /></template>
<style>
.ajl35wbzz {
  fill: currentColor;
  d: path("M2 22V9.975L9 7v2l5-2v3h8v12zm9-4h2v-4h-2zm-4 0h2v-4H7zm8 0h2v-4h-2zm6.8-9.5h-4.625l.85-6.5H21z");
}

</style>
