<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcy6a0pco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcy6a0pco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-sliders-fill" /></template>
