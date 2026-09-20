<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4a5z1bgo.css';
import '../../css/m/m1is6zbfj.css';
import '../../css/j/j26gprbnv.css';
import '../../css/h/h-o2zrbmc.css';
import '../../css/f/fnpmnwb6w.css';
import '../../css/f/f0pybpjrh.css';
import '../../css/c/cbur2_bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g><rect class="k4a5z1bgo"/><rect transform="rotate(30 12 12)" class="m1is6zbfj"/><rect transform="rotate(60 12 12)" class="j26gprbnv"/><rect transform="rotate(90 12 12)" class="h-o2zrbmc"/><rect transform="rotate(120 12 12)" class="fnpmnwb6w"/><rect transform="rotate(150 12 12)" class="f0pybpjrh"/><rect transform="rotate(180 12 12)" class="cbur2_bsk"/><animateTransform attributeName="transform" calcMode="discrete" dur="0.75s" repeatCount="indefinite" type="rotate" values="0 12 12;30 12 12;60 12 12;90 12 12;120 12 12;150 12 12;180 12 12;210 12 12;240 12 12;270 12 12;300 12 12;330 12 12;360 12 12"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:bars-rotate-fade" /></template>
