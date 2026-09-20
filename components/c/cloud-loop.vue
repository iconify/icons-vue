<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb5ayghuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path fill-opacity="0" d="M7 19h11c2.21 0 4 -1.79 4 -4c0 -2.21 -1.79 -4 -4 -4h-1v-1c0 -2.76 -2.24 -5 -5 -5c-2.42 0 -4.44 1.72 -4.9 4h-0.1c-2.76 0 -5 2.24 -5 5c0 2.76 2.24 5 5 5Z" class="tb5ayghuj"><animate attributeName="d" dur="12s" keyTimes="0;0.25;0.5;0.75;1" repeatCount="indefinite" values="M7 19h11c2.21 0 4 -1.79 4 -4c0 -2.21 -1.79 -4 -4 -4h-1v-1c0 -2.76 -2.24 -5 -5 -5c-2.42 0 -4.44 1.72 -4.9 4h-0.1c-2.76 0 -5 2.24 -5 5c0 2.76 2.24 5 5 5Z;M6 19h12c2.21 0 4 -1.79 4 -4c0 -2.21 -1.79 -4 -4 -4h0v-1c0 -2.76 -2.24 -5 -5 -5c-2.42 0 -4.44 1.72 -4.9 4h-2.1c-2.76 0 -5 2.24 -5 5c0 2.76 2.24 5 5 5Z;M6 19h11c2.21 0 4 -1.79 4 -4c0 -2.21 -1.79 -4 -4 -4h0v-1c0 -2.76 -2.24 -5 -5 -5c-2.42 0 -4.44 1.72 -4.9 4h-1.1c-2.76 0 -5 2.24 -5 5c0 2.76 2.24 5 5 5Z;M7 19h10c2.21 0 4 -1.79 4 -4c0 -2.21 -1.79 -4 -4 -4h0v-1c0 -2.76 -2.24 -5 -5 -5c-2.42 0 -4.44 1.72 -4.9 4h-0.1c-2.76 0 -5 2.24 -5 5c0 2.76 2.24 5 5 5Z;M7 19h11c2.21 0 4 -1.79 4 -4c0 -2.21 -1.79 -4 -4 -4h-1v-1c0 -2.76 -2.24 -5 -5 -5c-2.42 0 -4.44 1.72 -4.9 4h-0.1c-2.76 0 -5 2.24 -5 5c0 2.76 2.24 5 5 5Z"/><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="60;0"/><animate fill="freeze" attributeName="fill-opacity" begin="0.6s" dur="0.4s" to="1"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-loop" /></template>
