<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2wqd55dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2wqd55dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bar-chart-alt" /></template>
