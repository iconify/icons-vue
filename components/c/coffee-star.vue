<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc1y7ccgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc1y7ccgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coffee-star" /></template>
