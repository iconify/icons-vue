<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtfr4tbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":24};
const content = `<path class="dtfr4tbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:gulp" /></template>
