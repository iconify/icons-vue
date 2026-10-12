<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmfthdbsp.css';
import '../../css/w/w1s0n4bzt.css';
import '../../css/v/vij3r-vuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rmfthdbsp"/><path class="w1s0n4bzt"/><path class="vij3r-vuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cash-register-20-bold" /></template>
