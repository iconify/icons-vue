<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhku4kbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-minus-fill" /></template>
<style>
.lhku4kbyv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.92487 23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12C1 5.92487 5.92487 1 12 1ZM7.6 10.9C6.99249 10.9 6.5 11.3925 6.5 12C6.5 12.6075 6.99249 13.1 7.6 13.1H16.4C17.0075 13.1 17.5 12.6075 17.5 12C17.5 11.3925 17.0075 10.9 16.4 10.9H7.6Z");
}

</style>
