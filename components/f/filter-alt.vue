<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukuhlz15q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukuhlz15q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:filter-alt" /></template>
