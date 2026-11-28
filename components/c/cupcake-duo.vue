<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzzl3ybmf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/iv8z1eyqm.css';
import '../../css/f/fg2wsdb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzzl3ybmf secondary"/><g class="dt0cm9dhy primary"><path class="iv8z1eyqm"/><path class="fg2wsdb7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cupcake-duo" /></template>
