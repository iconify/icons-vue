<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1_r-zqlu.css';
import '../../css/l/l9dsd9ghz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1_r-zqlu"/><path class="l9dsd9ghz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-2-line" /></template>
