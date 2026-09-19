<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fef3nobpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fef3nobpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:apple" /></template>
