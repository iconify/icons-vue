<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud7qzlq2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ud7qzlq2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-armn-sha" /></template>
