<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzka1x0wa.css';
import '../../css/f/fjej9hboc.css';
import '../../css/c/cylywgbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qzka1x0wa"/><path class="fjej9hboc"/><path class="cylywgbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bed-linen" /></template>
