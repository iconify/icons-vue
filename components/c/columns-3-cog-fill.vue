<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5tq3cbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5tq3cbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-3-cog-fill" /></template>
