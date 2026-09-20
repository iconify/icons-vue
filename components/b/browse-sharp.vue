<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enx-1jbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:browse-sharp" /></template>
<style>
.enx-1jbqb {
  fill: currentColor;
  d: path("M4 20v-5h7v5zm9 0v-9h7v9zm-9-7V4h7v9zm9-4V4h7v5z");
}

</style>
