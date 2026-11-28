<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zjy7hntji.css';
import '../../css/m/m2hacq_bi.css';
import '../../css/g/g9z927bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zjy7hntji"/><path class="m2hacq_bi"/><path class="g9z927bqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flip-vertical" /></template>
