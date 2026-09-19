<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8mrcm4_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w8mrcm4_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:hns" /></template>
