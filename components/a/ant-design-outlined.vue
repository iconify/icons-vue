<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt25qkitr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xt25qkitr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:ant-design-outlined" /></template>
