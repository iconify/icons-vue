<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq2d1ubnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq2d1ubnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-imagine" /></template>
