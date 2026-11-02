<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq7wvsbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq7wvsbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-control-point-fill" /></template>
