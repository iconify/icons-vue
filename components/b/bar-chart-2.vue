<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eczgn9bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eczgn9bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:bar-chart-2" /></template>
