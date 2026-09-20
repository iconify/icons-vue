<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfnvg26lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lfnvg26lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:key" /></template>
