<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w958mfb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-document-outline-sharp" /></template>
<style>
.w958mfb2v {
  fill: currentColor;
  d: path("M13.654 21v-2.21l5.96-5.934l2.19 2.204l-5.94 5.94zm6.885-5.94l-.926-.945zm-6 5.056h.95l3.467-3.474l-.45-.494l-.475-.47l-3.493 3.488zM5 21V3h9.5L19 7.5v2.596h-1V8h-4V4H6v16h5.27v1zm13.506-4.852l-.475-.47l.925.964z");
}

</style>
