<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9bpb6big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n9bpb6big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dingtalk-square-fill" /></template>
