<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swgykjbfw.css';
import '../../css/z/z_9dnnd4s.css';
import '../../css/f/fc28b1b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swgykjbfw"/><path class="z_9dnnd4s"/><path class="fc28b1b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:langfuse" /></template>
