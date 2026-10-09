<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjt2vnb6p.css';
import '../../css/a/axzye1lxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pjt2vnb6p"/><path class="axzye1lxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:copy-20" /></template>
