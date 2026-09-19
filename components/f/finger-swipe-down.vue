<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qozmdccui.css';
import '../../css/z/zvp6zsbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qozmdccui"/><path class="zvp6zsbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-swipe-down" /></template>
