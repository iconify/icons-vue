<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sunc94b1a.css';
import '../../css/e/ewqp1cbed.css';
import '../../css/f/ficmb5hae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sunc94b1a"/><path class="ewqp1cbed"/><path class="ficmb5hae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-broadcast-tower-filled" /></template>
