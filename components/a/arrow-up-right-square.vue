<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej_ysgt9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_ysgt9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-up-right-square" /></template>
