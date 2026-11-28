<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpsncfb9w.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/ssn2did6s.css';
import '../../css/p/p70x4lbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tpsncfb9w"/><g class="dt0cm9dhy primary"><path class="ssn2did6s"/><path class="p70x4lbvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:eyedropper-duo" /></template>
