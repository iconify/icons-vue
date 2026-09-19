<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgeipghhv.css';
import '../../css/n/npf-mpbxr.css';
import '../../css/c/cofxwr0zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kgeipghhv"/><path class="npf-mpbxr"/><path class="cofxwr0zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:database-twotone" /></template>
