<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zptxq6btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zptxq6btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:landscape" /></template>
