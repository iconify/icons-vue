<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m66w98bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m66w98bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:browser-rtl" /></template>
