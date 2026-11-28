<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtjs5r6lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtjs5r6lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:euro" /></template>
