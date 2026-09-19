<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw10q5bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="yw10q5bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:googleplus-rect" /></template>
