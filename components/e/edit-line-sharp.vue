<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsdc4kb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-line-sharp" /></template>
<style>
.nsdc4kb_p {
  fill: currentColor;
  d: path("M4 20v-2.52L17.914 3.555l2.526 2.544L6.52 20zM17.504 7.589L19 6.111L17.889 5l-1.477 1.496zM9.896 20l1-1H21v1z");
}

</style>
