<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhxhmzp8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nhxhmzp8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:frown-fill" /></template>
