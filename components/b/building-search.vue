<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x30gos8ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x30gos8ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:building-search" /></template>
