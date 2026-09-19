<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtx0be1eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gtx0be1eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gemini-filled" /></template>
