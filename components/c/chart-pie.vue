<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqxfambte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqxfambte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:chart-pie" /></template>
