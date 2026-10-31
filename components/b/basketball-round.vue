<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsp2g4brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsp2g4brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:basketball-round" /></template>
