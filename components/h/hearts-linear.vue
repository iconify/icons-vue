<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sty21ibsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sty21ibsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hearts-linear" /></template>
