<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljaw0iz7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ljaw0iz7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:kubernetes-outlined" /></template>
