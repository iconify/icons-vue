<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tckig-5-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tckig-5-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:import-export" /></template>
