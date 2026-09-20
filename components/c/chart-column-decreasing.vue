<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoazkfs-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoazkfs-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-column-decreasing" /></template>
