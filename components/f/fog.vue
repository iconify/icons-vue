<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g8zko0f9l.css';
import '../../css/m/mw9akibpt.css';
import '../../css/h/hhblzq4_i.css';
import '../../css/r/r0cayg01m.css';
import '../../css/w/w-ulw3ceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="g8zko0f9l"/><path class="mw9akibpt"/><path class="hhblzq4_i"/><path class="r0cayg01m"/><path class="w-ulw3ceb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:fog" /></template>
