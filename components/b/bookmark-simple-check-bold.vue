<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl1-wob7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dl1-wob7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-check-bold" /></template>
