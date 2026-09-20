<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg53ypbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kg53ypbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:expo" /></template>
