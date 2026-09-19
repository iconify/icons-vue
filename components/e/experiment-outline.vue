<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm4_r2bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dm4_r2bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:experiment-outline" /></template>
