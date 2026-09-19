<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g67g2gbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g67g2gbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-jpg" /></template>
