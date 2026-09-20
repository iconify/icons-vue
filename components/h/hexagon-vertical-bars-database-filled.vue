<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/a4opz1bbj.css';
import '../../css/g/g1fovbbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="a4opz1bbj"/><path class="g1fovbbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hexagon-vertical-bars-database-filled" /></template>
