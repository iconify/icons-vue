<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7yndj7yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="y7yndj7yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:code" /></template>
