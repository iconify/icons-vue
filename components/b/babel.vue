<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hcm8reluy.css';
import '../../css/r/rou0gmbnx.css';
import '../../css/u/ukj1ozbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="hcm8reluy"/><path class="rou0gmbnx"/><path class="ukj1ozbdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:babel" /></template>
