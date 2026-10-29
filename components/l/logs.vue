<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_qpl3blu.css';
import '../../css/r/r3oki5bqe.css';
import '../../css/g/gus4l3bgw.css';
import '../../css/g/gm4r5fzam.css';
import '../../css/s/skvw0vpph.css';
import '../../css/w/wbvjwjwto.css';
import '../../css/i/i020r9byc.css';
import '../../css/i/i7_s81bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_qpl3blu wm-shadow"/><path class="r3oki5bqe wm-k"/><path class="gus4l3bgw wm-k"/><path class="gm4r5fzam wm-k"/><path class="skvw0vpph wm-k"/><path class="wbvjwjwto wm-shine"/><path class="i020r9byc wm-k"/><path class="i7_s81bsb wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:logs" /></template>
