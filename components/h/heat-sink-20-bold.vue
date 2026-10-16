<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrq7csbic.css';
import '../../css/k/kbvc24bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nrq7csbic"/><path class="kbvc24bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-sink-20-bold" /></template>
