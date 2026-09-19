<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv_-h5b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nv_-h5b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-chart-bar-16-solid" /></template>
