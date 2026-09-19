<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo6c3-5uk.css';
import '../../css/t/t9axjb05q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fo6c3-5uk"/><path class="t9axjb05q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:enumeration-definition" /></template>
