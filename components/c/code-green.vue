<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqnggccsm.css';
import '../../css/x/x0ujg73is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqnggccsm"/><path class="x0ujg73is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:code-green" /></template>
