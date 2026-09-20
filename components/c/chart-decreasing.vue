<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi9mmib_a.css';
import '../../css/i/i9m88b1-u.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/krluo5bfx.css';
import '../../css/i/i4ohfdc0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zi9mmib_a"/><path class="i9m88b1-u"/><g class="ij2x_72vy"><path class="krluo5bfx"/><path class="i4ohfdc0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chart-decreasing" /></template>
