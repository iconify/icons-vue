<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_dvs5dfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_dvs5dfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:desktop" /></template>
