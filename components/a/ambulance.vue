<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n41l_qsqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n41l_qsqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ambulance" /></template>
