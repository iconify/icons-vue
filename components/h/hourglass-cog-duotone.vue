<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vwi8pd0fk.css';
import '../../css/n/nu9eyw4up.css';
import '../../css/h/hk5zoibhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vwi8pd0fk"/><path class="nu9eyw4up"/><path class="hk5zoibhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hourglass-cog-duotone" /></template>
