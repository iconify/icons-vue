<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq3q3bfsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sq3q3bfsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:calculator-not-equal-to" /></template>
