<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaa-d32jp.css';
import '../../css/q/qigsuypiz.css';
import '../../css/c/c8bngupzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eaa-d32jp"/><path class="qigsuypiz"/><path class="c8bngupzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cupcake-20-bold" /></template>
