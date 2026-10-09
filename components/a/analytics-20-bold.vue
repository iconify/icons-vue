<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdiltt19v.css';
import '../../css/r/rvji97b-y.css';
import '../../css/h/hsuwmebtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdiltt19v"/><path class="rvji97b-y"/><path class="hsuwmebtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:analytics-20-bold" /></template>
