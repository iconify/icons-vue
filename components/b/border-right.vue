<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa6qclbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa6qclbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:border-right" /></template>
