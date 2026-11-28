<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8fewte9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8fewte9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-chart-check" /></template>
