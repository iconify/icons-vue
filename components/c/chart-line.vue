<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecsrbub4u.css';
import '../../css/j/j5k2n0bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ecsrbub4u"/><path class="j5k2n0bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:chart-line" /></template>
