<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3q4fbcar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3q4fbcar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-3-square" /></template>
