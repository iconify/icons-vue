<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy-xykbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy-xykbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-tl-square" /></template>
