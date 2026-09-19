<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh0_ewbrk.css';
import '../../css/b/bwbmeku4p.css';
import '../../css/y/yp5ecdcuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sh0_ewbrk"/><path class="bwbmeku4p"/><path class="yp5ecdcuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:lock-twotone" /></template>
