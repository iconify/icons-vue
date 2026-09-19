<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qckt124lo.css';
import '../../css/c/c8kuy_ape.css';
import '../../css/f/ftm-s_hiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qckt124lo"/><circle class="c8kuy_ape"/><path class="ftm-s_hiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:instance-bx" /></template>
