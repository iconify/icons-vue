<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h165r_jwh.css';
import '../../css/p/p783iebym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><circle class="h165r_jwh"/><path class="p783iebym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-reason" /></template>
