<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2avr2bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2avr2bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-stroke-square-filled" /></template>
