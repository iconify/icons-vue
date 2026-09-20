<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huda90bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="huda90bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:full-height" /></template>
