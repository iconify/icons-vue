<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx_o-7mra.css';
import '../../css/x/xonpjubig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hx_o-7mra"/><path class="xonpjubig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-boat-20-bold" /></template>
