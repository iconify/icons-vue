<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl370cbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl370cbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:crown" /></template>
