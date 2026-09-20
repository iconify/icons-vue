<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co4_38baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-b-and-w-outline-sharp" /></template>
<style>
.co4_38baj {
  fill: currentColor;
  d: path("M20 20H4V4h16zM5.02 19h6.99v-8L19 19.02V5h-6.99v6z");
}

</style>
