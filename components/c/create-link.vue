<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf8cllhgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yf8cllhgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:create-link" /></template>
