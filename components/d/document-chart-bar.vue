<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oox843b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oox843b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:document-chart-bar" /></template>
