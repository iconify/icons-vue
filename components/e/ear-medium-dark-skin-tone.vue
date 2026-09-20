<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfx2wkbme.css';
import '../../css/a/a4-eoy1ky.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/ty0jp0byr.css';
import '../../css/z/zyiv9wvjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lfx2wkbme"/><path class="a4-eoy1ky"/><g class="ij2x_72vy"><path class="ty0jp0byr"/><path class="zyiv9wvjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ear-medium-dark-skin-tone" /></template>
