<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3xsz8tbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u3xsz8tbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:browser-multiple-window-solid" /></template>
