<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt6q08rtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jt6q08rtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:arrow-down" /></template>
