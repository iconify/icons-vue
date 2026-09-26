<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-itrpxnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-9-fill" /></template>
<style>
.e-itrpxnv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.9249 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1ZM13 6C13 5.4477 12.5523 5 12 5C11.4477 5 11 5.4477 11 6L11 11L7 11C6.4477 11 6 11.4477 6 12C6 12.5523 6.4477 13 7 13L12 13C12.5523 13 13 12.5523 13 12L13 6Z");
}

</style>
