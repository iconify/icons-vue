<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfe_5bbnt.css';
import '../../css/p/pa2w7dcbl.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/ty0jp0byr.css';
import '../../css/z/zyiv9wvjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kfe_5bbnt"/><path class="pa2w7dcbl"/><g class="ij2x_72vy"><path class="ty0jp0byr"/><path class="zyiv9wvjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ear" /></template>
