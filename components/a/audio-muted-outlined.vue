<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joucdub-z.css';
import '../../css/h/hwp54b9_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="joucdub-z"/><path class="hwp54b9_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:audio-muted-outlined" /></template>
