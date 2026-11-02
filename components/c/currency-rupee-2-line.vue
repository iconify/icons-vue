<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpqc9_8ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpqc9_8ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rupee-2-line" /></template>
