<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gupt5drld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gupt5drld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:drag" /></template>
