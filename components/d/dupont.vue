<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxgotib5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":138.039,"height":40.145,"left":-1.136,"top":-1.136};
const content = `<path class="hxgotib5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dupont" /></template>
