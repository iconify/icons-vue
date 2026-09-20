<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejqtkhbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:docs-add-on" /></template>
<style>
.ejqtkhbqt {
  fill: currentColor;
  d: path("M16.5 20.475v-3h-3v-1h3v-3h1v3h3v1h-3v3zM4.5 17.5v-1h7.017q-.017.265-.004.505q.012.24.03.495zm0-4v-1h9.304q-.287.208-.538.458q-.25.25-.485.542zm0-4v-1h14v1zm0-4v-1h14v1z");
}

</style>
