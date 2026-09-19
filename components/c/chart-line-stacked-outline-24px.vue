<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biil5ne2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biil5ne2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-line-stacked-outline-24px" /></template>
