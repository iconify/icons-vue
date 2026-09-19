<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doplcl7zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-minus" /></template>
<style>
.doplcl7zi {
  fill: currentColor;
  d: path("M19 12.998H5v-2h14z");
}

</style>
