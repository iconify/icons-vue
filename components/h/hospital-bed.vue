<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfcmd9bxj.css';
import '../../css/g/gv22t7b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dfcmd9bxj"/><path class="gv22t7b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hospital-bed" /></template>
