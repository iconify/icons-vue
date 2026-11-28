<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1n6r1x6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d1n6r1x6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:group-light" /></template>
