<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh6cq-brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qh6cq-brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-top-bold" /></template>
