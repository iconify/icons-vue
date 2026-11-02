<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryf94lbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryf94lbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:celsius-line" /></template>
