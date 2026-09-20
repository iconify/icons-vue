<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx3d5nk4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-french-sharp" /></template>
<style>
.sx3d5nk4i {
  fill: currentColor;
  d: path("M5 16.5v-9h6v1H6v3h4v1H6v4zm8 0v-9h4.789L19 8.711v2.77l-1.211 1.211h-.831L19 16.5h-1.08l-2.068-3.808H14V16.5zm1-4.808h3.327L18 11.02V9.173l-.673-.673H14z");
}

</style>
