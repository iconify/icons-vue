<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7fa6mi_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7fa6mi_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:line-dot-right-horizontal" /></template>
