<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdq6guqpt.css';
import '../../css/m/ma8xebchi.css';
import '../../css/j/jops46icm.css';
import '../../css/s/soxgggbzu.css';
import '../../css/n/n2-6f21cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kdq6guqpt"/><path class="ma8xebchi"/><path class="jops46icm"/><path class="soxgggbzu"/><path class="n2-6f21cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dyalog" /></template>
