<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l8j7uhbgb.css';
import '../../css/u/uoskdrb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l8j7uhbgb"/><path clip-rule="evenodd" class="uoskdrb1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hospital-symbol-outline-24px" /></template>
