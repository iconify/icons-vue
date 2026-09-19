<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on3n-9bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="on3n-9bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:download-outlined" /></template>
