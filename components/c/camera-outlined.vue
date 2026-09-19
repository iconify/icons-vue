<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmld6fb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lmld6fb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:camera-outlined" /></template>
