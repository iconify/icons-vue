<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f-72ljw4x.css';
import '../../css/j/joz8m6uoh.css';
import '../../css/h/hp8nadcvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f-72ljw4x"/><path class="joz8m6uoh"/><path class="hp8nadcvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:coffee" /></template>
