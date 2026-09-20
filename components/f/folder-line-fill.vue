<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrn_u-bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrn_u-bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-line-fill" /></template>
