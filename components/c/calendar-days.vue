<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/ml6gccbzj.css';
import '../../css/j/jhxi-trnl.css';
import '../../css/y/yg0tartzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ml6gccbzj"/><rect class="jhxi-trnl"/><path class="yg0tartzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:calendar-days" /></template>
