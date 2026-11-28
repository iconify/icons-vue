<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miq6brhkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miq6brhkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chess-bishop" /></template>
