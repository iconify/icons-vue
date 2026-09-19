<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9pxw5fcl.css';
import '../../css/a/afvukzbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e9pxw5fcl"/><path class="afvukzbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-download" /></template>
