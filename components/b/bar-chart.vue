<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc5e8lyyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc5e8lyyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:bar-chart" /></template>
