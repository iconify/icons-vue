<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn8wa8oth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn8wa8oth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:line-chart-down" /></template>
