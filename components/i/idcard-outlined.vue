<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4corvbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p4corvbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:idcard-outlined" /></template>
