<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av9ti37jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="av9ti37jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:insert-row-left-outlined" /></template>
