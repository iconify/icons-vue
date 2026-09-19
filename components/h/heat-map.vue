<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl_9c8bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fl_9c8bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:heat-map" /></template>
