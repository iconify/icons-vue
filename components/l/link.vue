<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqu73ccux.css';
import '../../css/c/ccr-r5nke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqu73ccux"/><path class="ccr-r5nke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:link" /></template>
