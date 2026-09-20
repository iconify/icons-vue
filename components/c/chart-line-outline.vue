<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj7w25rnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj7w25rnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:chart-line-outline" /></template>
