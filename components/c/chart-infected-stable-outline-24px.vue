<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hkx42l5xa.css';
import '../../css/m/me4jii-pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hkx42l5xa"/><path clip-rule="evenodd" class="me4jii-pw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-infected-stable-outline-24px" /></template>
