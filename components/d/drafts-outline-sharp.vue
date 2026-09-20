<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4g9elb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drafts-outline-sharp" /></template>
<style>
.c4g9elb0o {
  fill: currentColor;
  d: path("m12 1l10 5.975V21H2V6.975zm0 11.65L19.8 8L12 3.35L4.2 8zM12 15l-8-4.8V19h16v-8.8zm0 4h8H4z");
}

</style>
