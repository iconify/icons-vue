<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bba6be8ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kine" /></template>
<style>
.bba6be8ug {
  fill: var(--svg-color--12a8a7, #12a8a7);
  fill-rule: evenodd;
  d: path("M4.2 3h5.4v5.4H4.2zm0 12.6h5.4V21H4.2zM9 12l6-9h4.8l-5.7 9l5.7 9H15z");
}

</style>
