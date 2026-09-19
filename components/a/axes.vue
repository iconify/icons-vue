<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcimo1b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcimo1b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:axes" /></template>
