<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy88k1nit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:docs-outline-sharp" /></template>
<style>
.xy88k1nit {
  fill: currentColor;
  d: path("M13.654 3L18 7.462V21H6V3zM11.5 4H7v16h10V9.673h-5.5zm1 0v4.673H17v-.79L13.252 4zM9.654 18.173v-1H12.5v1zm0-3.788v-1h4.673v1z");
}

</style>
