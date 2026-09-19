<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2m5zi2on.css';
import '../../css/y/yadluib6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y2m5zi2on"/><path class="yadluib6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-ibv" /></template>
