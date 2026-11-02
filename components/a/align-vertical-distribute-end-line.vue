<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq5lvnzqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq5lvnzqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-distribute-end-line" /></template>
