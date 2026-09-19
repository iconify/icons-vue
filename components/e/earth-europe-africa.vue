<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wafu_qb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wafu_qb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:earth-europe-africa" /></template>
