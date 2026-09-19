<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb413xbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb413xbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circles-9" /></template>
