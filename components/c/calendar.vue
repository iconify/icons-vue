<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz6p9fyrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gz6p9fyrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:calendar" /></template>
