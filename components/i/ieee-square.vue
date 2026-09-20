<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwnuoacob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qwnuoacob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ieee-square" /></template>
