<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz9gb9bqr.css';
import '../../css/r/rndnw4b9p.css';
import '../../css/x/xray__lap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="uz9gb9bqr"/><path class="rndnw4b9p"/><path class="xray__lap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:baggage-claim" /></template>
