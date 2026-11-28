<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psqsc1boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="psqsc1boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chart-area-bold" /></template>
