<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d1i2iw-bc.css';
import '../../css/c/c5_8_gb4c.css';
import '../../css/s/s8ub28b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d1i2iw-bc"/><path class="c5_8_gb4c"/><path class="s8ub28b-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-collapse-duo" /></template>
