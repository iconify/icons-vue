<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_rj89vzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x_rj89vzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:border-right" /></template>
