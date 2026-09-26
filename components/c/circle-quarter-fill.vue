<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqe91nbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-quarter-fill" /></template>
<style>
.rqe91nbpj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12ZM12 5C15.866 5 19 8.134 19 12C19 12.5523 18.5523 13 18 13L12 13C11.4477 13 11 12.5523 11 12L11 6C11 5.4477 11.4477 5 12 5Z");
}

</style>
