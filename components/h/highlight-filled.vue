<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywa-3-i-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ywa-3-i-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:highlight-filled" /></template>
