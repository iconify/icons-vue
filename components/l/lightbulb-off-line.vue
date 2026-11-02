<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvt_mub5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvt_mub5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lightbulb-off-line" /></template>
