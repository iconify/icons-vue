<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cb89wsg7d.css';
import '../../css/g/g3tbz9iqf.css';
import '../../css/y/ydll70ntu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cb89wsg7d"/><path clip-rule="evenodd" class="g3tbz9iqf"/><path clip-rule="evenodd" class="ydll70ntu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:layers" /></template>
