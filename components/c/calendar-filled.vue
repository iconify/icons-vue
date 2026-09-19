<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1024j9lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1024j9lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:calendar-filled" /></template>
