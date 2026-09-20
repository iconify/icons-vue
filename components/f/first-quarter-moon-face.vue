<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_5l8lb9a.css';
import '../../css/i/io3w-rbsf.css';
import '../../css/g/g7_albbtb.css';
import '../../css/v/v415fabhh.css';
import '../../css/o/o83e2bcbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="f_5l8lb9a"/><path class="io3w-rbsf"/><circle class="g7_albbtb"/><path class="v415fabhh"/><path class="o83e2bcbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:first-quarter-moon-face" /></template>
