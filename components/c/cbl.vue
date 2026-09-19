<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un6mu3bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="un6mu3bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cbl" /></template>
