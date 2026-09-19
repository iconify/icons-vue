<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynum6zy-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynum6zy-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-3-square-bold" /></template>
