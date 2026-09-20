<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f46mr-fii.css';
import '../../css/i/ie50nzixu.css';
import '../../css/m/mow89gbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f46mr-fii"/><path class="ie50nzixu"/><path class="mow89gbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dollar-down" /></template>
