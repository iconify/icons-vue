<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-77igb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c-77igb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dribbble-square-outlined" /></template>
