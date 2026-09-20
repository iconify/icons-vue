<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdua9vbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qdua9vbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:editor-grid" /></template>
