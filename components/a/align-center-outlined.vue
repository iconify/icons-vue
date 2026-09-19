<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhst8qbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nhst8qbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:align-center-outlined" /></template>
