<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysbx4jb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysbx4jb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:fan-handheld" /></template>
