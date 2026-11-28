<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/saij5kb4t.css';
import '../../css/n/n3xvoccbk.css';
import '../../css/t/te09yrbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="saij5kb4t"/><path class="n3xvoccbk"/><path class="te09yrbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-to-line" /></template>
