<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_8b_c5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_8b_c5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-reload-outline" /></template>
