<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-u9j3wiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k-u9j3wiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gift-outline" /></template>
