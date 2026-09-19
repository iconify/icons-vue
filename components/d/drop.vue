<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_hkmpbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m_hkmpbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:drop" /></template>
