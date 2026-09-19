<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up-kybbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="up-kybbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-image" /></template>
