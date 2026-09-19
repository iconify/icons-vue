<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybqt-ybyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybqt-ybyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-up" /></template>
