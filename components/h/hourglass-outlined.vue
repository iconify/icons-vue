<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdgm4mbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bdgm4mbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:hourglass-outlined" /></template>
