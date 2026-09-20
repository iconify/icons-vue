<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtj1kerrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtj1kerrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:basketball-line" /></template>
