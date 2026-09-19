<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj_wmgb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xj_wmgb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrow-up-right" /></template>
