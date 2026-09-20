<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5ras0q8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5ras0q8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:line-style" /></template>
