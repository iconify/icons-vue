<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m3q5dgd3j.css';
import '../../css/z/z5isr3bvu.css';
import '../../css/c/ce7yr5b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="m3q5dgd3j"/><path vector-effect="non-scaling-stroke" class="z5isr3bvu"/><path vector-effect="non-scaling-stroke" class="ce7yr5b1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-list-numbered-rtl" /></template>
