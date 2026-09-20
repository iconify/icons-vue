<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4oh-kbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-3-sharp" /></template>
<style>
.p4oh-kbtv {
  fill: currentColor;
  d: path("M9 17h6V7H9v2h4v2h-2v2h2v2H9zm-6 4V3h18v18z");
}

</style>
