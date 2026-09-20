<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr0ize7uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr0ize7uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chess-rook" /></template>
