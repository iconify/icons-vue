<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnd5ksvsr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dca2urprn.css';
import '../../css/x/x0cxdwb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnd5ksvsr secondary"/><g class="dt0cm9dhy primary"><path class="dca2urprn"/><path class="x0cxdwb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:house-crack-duo" /></template>
