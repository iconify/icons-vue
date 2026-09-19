<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o727yzb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o727yzb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:copy" /></template>
