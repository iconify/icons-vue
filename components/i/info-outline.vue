<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc4qgwbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lc4qgwbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:info-outline" /></template>
