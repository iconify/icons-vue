<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu6la5bgc.css';
import '../../css/f/fhhuixbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tu6la5bgc"/><path class="fhhuixbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exit-fill-16" /></template>
