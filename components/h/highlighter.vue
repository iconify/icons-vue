<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsg68bc0n.css';
import '../../css/p/psgh11omp.css';
import '../../css/i/ixobe5ich.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="psgh11omp"/><path class="ixobe5ich"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:highlighter" /></template>
