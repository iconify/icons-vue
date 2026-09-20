<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz4b90hlv.css';
import '../../css/h/hltafxbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="oz4b90hlv"/><path class="hltafxbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:anger-symbol" /></template>
