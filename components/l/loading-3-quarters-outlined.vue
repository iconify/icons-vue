<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9x_81bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e9x_81bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:loading-3-quarters-outlined" /></template>
