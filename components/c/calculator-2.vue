<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdnudpugi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mdnudpugi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calculator-2" /></template>
