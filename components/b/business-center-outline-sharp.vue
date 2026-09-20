<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol21qlbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:business-center-outline-sharp" /></template>
<style>
.ol21qlbcl {
  fill: currentColor;
  d: path("M3 20V7h6V4h6v3h6v13zm7-13h4V5h-4zm10 7.5h-6V16h-4v-1.5H4V19h16zm-9 .5h2v-2h-2zm-7-1.5h6V12h4v1.5h6V8H4zm8 .5");
}

</style>
