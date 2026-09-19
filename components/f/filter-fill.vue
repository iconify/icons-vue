<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggiwcjb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ggiwcjb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:filter-fill" /></template>
