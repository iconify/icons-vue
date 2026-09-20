<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaop-ogzu.css';
import '../../css/w/w8tcc-b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gaop-ogzu"/><path class="w8tcc-b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-medical-notes" /></template>
