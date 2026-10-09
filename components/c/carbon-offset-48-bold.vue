<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6eu_k3xl.css';
import '../../css/f/f9l75pbbf.css';
import '../../css/q/q736ljmrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g6eu_k3xl"/><path class="f9l75pbbf"/><path class="q736ljmrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-offset-48-bold" /></template>
