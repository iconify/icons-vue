<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/te85glbsz.css';
import '../../css/e/emnsetb8o.css';
import '../../css/t/ts76sqbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect transform="rotate(-90 15 9)" class="te85glbsz"/><path class="emnsetb8o"/><path class="ts76sqbbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:line-in-alt-light" /></template>
