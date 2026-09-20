<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5rb22bzv.css';
import '../../css/a/az0-jcc3g.css';
import '../../css/a/a847c404k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5rb22bzv"/><path class="az0-jcc3g"/><path class="a847c404k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dawarich-dark" /></template>
