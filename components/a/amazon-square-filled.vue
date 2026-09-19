<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db8k76whz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="db8k76whz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:amazon-square-filled" /></template>
