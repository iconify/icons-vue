<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo70snbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mo70snbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-square-fill-20" /></template>
