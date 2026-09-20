<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojnu-8dvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojnu-8dvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-horizontal-line" /></template>
