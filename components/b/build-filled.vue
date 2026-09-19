<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neidi-lvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="neidi-lvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:build-filled" /></template>
