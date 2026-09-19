<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p59xlhsbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1472};
const content = `<g transform="translate(0 1472) scale(1 -1)"><path class="p59xlhsbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-down" /></template>
