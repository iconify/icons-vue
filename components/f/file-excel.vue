<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znhln2gbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="znhln2gbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-excel" /></template>
