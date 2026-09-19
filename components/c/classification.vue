<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qerqc_trz.css';
import '../../css/g/g3fxfcd6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="qerqc_trz"/><path class="g3fxfcd6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:classification" /></template>
