<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej58xi1_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ej58xi1_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:board-hanging-rail" /></template>
