<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsi3rkp0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsi3rkp0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cursor-click-20-bold" /></template>
