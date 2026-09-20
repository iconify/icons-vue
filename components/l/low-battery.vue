<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c87o6pbte.css';
import '../../css/m/mfap_hbod.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/c/cuy0u_kfh.css';
import '../../css/g/gxk1hu3mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c87o6pbte"/><path class="mfap_hbod"/><g class="jn8qy4bru"><path class="cuy0u_kfh"/><path class="gxk1hu3mk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:low-battery" /></template>
