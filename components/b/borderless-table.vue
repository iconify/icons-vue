<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4_tterzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i4_tterzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:borderless-table" /></template>
