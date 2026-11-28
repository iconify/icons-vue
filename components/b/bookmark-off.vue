<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvtwf7mtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvtwf7mtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bookmark-off" /></template>
