<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yptr5ybnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yptr5ybnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:grids" /></template>
