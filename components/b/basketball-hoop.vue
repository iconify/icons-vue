<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yryksubcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yryksubcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:basketball-hoop" /></template>
