<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyjewcbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-open-sharp" /></template>
<style>
.wyjewcbbi {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v2H4v10l2.4-8h17.1l-3 10z");
}

</style>
