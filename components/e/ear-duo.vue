<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g11d8ebst.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hkoz73s2u.css';
import '../../css/f/fis0j1bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g11d8ebst secondary"/><g class="dt0cm9dhy primary"><path class="hkoz73s2u"/><path class="fis0j1bmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ear-duo" /></template>
