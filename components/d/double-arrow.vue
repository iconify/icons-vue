<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5-1y4y0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":312,"height":496};
const content = `<path class="n5-1y4y0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:double-arrow" /></template>
