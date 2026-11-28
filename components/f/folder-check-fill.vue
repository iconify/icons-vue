<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daf5wab8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="daf5wab8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:folder-check-fill" /></template>
