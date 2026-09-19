<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfd8uw_5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rfd8uw_5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:double-right-outlined" /></template>
