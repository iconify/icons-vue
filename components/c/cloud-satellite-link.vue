<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unaljlb8v.css';
import '../../css/s/szt_lz6ub.css';
import '../../css/l/l71mrm8fk.css';
import '../../css/h/hh_hn2b_u.css';
import '../../css/m/m4ajnwsrg.css';
import '../../css/f/fjvik3r7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="unaljlb8v"/><path class="szt_lz6ub"/><circle class="l71mrm8fk"/><path class="hh_hn2b_u"/><circle class="m4ajnwsrg"/><path class="fjvik3r7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-satellite-link" /></template>
