<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu0vtk99p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bu0vtk99p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bone-solid" /></template>
