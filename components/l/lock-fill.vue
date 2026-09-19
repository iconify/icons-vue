<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar5b5-zjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ar5b5-zjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:lock-fill" /></template>
