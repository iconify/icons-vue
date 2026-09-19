<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns-ktm3kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns-ktm3kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bar-chart-alt-2" /></template>
