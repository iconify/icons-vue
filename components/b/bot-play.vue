<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej8fvvbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej8fvvbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bot-play" /></template>
