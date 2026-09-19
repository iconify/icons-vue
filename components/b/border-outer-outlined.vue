<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp83qqbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jp83qqbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:border-outer-outlined" /></template>
