<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bug6acbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bug6acbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-markdown-outlined" /></template>
