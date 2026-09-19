<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzuzrbxyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wzuzrbxyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:db2-database" /></template>
