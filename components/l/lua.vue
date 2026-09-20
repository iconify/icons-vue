<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5xe79bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e5xe79bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lua" /></template>
