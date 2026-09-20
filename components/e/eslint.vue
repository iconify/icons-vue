<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fipcg1rcz.css';
import '../../css/g/gtk4lacos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fipcg1rcz"/><path class="gtk4lacos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:eslint" /></template>
