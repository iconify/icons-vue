<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl_peyboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yl_peyboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:aeon" /></template>
