<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp03mxf5g.css';
import '../../css/a/aqszcbwbb.css';
import '../../css/f/f7o03acte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp03mxf5g"/><circle class="aqszcbwbb"/><circle class="f7o03acte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bus-school" /></template>
