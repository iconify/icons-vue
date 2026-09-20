<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yxrw5gbvw.css';
import '../../css/f/fnba-4b3q.css';
import '../../css/p/ppj72pith.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yxrw5gbvw"/><path class="fnba-4b3q"/><path class="ppj72pith"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-fork-sharp-two-tone" /></template>
