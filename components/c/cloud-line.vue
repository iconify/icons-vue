<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy-c_r29m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy-c_r29m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-line" /></template>
