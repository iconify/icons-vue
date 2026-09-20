<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs7v8dblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qs7v8dblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fahrenheit" /></template>
