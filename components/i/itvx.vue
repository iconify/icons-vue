<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aty1gwanu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aty1gwanu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:itvx" /></template>
