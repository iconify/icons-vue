<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d__xc-bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d__xc-bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:loading-outline" /></template>
