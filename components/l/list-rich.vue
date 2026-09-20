<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy2-xpbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yy2-xpbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:list-rich" /></template>
