<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omu23ub3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omu23ub3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ferris-wheel" /></template>
