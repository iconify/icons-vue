<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdtr5e43k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fdtr5e43k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-geor-man" /></template>
