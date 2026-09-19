<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpzhsfboj.css';
import '../../css/i/i8a34cbqw.css';
import '../../css/x/xxpqapb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xpzhsfboj"/><path class="i8a34cbqw"/><path class="xxpqapb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-minimum" /></template>
