<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlr4lquzx.css';
import '../../css/v/vdsszm8qt.css';
import '../../css/f/fheposbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="nlr4lquzx"/><path class="vdsszm8qt"/><path class="fheposbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-instagram" /></template>
