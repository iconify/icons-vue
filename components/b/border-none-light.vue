<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vygsdebey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vygsdebey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-none-light" /></template>
