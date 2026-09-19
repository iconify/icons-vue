<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj5vjvkzr.css';
import '../../css/b/b12gxvr_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5vjvkzr"/><circle class="b12gxvr_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-yin-yang" /></template>
