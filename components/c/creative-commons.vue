<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hieikacsf.css';
import '../../css/d/dp-b6abae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hieikacsf"/><path class="dp-b6abae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:creative-commons" /></template>
