<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry_r6gbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry_r6gbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:blu-os" /></template>
