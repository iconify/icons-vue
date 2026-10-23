<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odelaxbie.css';
import '../../css/w/wuhamvb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":400};
const content = `<path class="odelaxbie"/><path class="wuhamvb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:backloggd" /></template>
