<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voq8q4hpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voq8q4hpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-echarts" /></template>
