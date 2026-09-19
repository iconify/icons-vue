<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt87vo4px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dt87vo4px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-very-sad-stroke-12" /></template>
