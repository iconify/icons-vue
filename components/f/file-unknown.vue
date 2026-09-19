<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1zkwsbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l1zkwsbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-unknown" /></template>
