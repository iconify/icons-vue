<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjhesdb2l.css';
import '../../css/e/efh5-1q6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjhesdb2l"/><path class="efh5-1q6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-vertical-20-bold" /></template>
