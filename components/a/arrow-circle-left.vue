<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te0_z2frq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te0_z2frq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:arrow-circle-left" /></template>
