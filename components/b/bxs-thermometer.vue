<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyzn85bno.css';
import '../../css/t/tky-zccgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyzn85bno"/><path class="tky-zccgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-thermometer" /></template>
