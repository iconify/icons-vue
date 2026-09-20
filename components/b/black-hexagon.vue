<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl7_itbah.css';
import '../../css/i/i8zs08y5g.css';
import '../../css/e/es2jbccom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xl7_itbah"/><path class="i8zs08y5g"/><path class="es2jbccom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-hexagon" /></template>
