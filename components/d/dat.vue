<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy44idbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gy44idbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dat" /></template>
