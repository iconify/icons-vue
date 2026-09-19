<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh1d9-p_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xh1d9-p_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dropbox-outline" /></template>
