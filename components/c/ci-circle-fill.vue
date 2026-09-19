<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc0fmsbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tc0fmsbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:ci-circle-fill" /></template>
