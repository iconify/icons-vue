<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bti2zsyuz.css';
import '../../css/h/hzelccctm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bti2zsyuz"/><path class="hzelccctm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dashboard-20-bold" /></template>
