<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uitlmqh0r.css';
import '../../css/g/g_oiv7bye.css';
import '../../css/q/qexqi5bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uitlmqh0r"/><path class="g_oiv7bye"/><circle class="qexqi5bar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-tripod" /></template>
