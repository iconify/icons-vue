<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ujn-f1vfa.css';
import '../../css/y/yf9dsibnw.css';
import '../../css/f/ftve-cbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ujn-f1vfa"/><path class="wm-a yf9dsibnw"/><path class="ftve-cbmp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-bucket" /></template>
