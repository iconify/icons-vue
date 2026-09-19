<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cklww9brb.css';
import '../../css/i/i0mrvmytj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cklww9brb"/><path class="i0mrvmytj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:calendar-twotone" /></template>
