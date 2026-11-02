<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smi8o-ccw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smi8o-ccw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-horizontal-line" /></template>
