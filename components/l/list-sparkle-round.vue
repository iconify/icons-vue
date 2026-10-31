<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2-d9v4-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2-d9v4-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-sparkle-round" /></template>
