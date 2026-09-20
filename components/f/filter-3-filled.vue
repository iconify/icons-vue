<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd3xdgnmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="yd3xdgnmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:filter-3-filled" /></template>
