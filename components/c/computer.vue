<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pvu1pxbbe.css';
import '../../css/e/eg88gnbzy.css';
import '../../css/g/g0bsq3byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pvu1pxbbe"/><path class="eg88gnbzy"/><path class="g0bsq3byr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:computer" /></template>
