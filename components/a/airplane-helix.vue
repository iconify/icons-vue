<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufie9ebgy.css';
import '../../css/g/guewfbcxi.css';
import '../../css/f/f4er-0bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ufie9ebgy"><path class="guewfbcxi"/><path clip-rule="evenodd" class="f4er-0bna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:airplane-helix" /></template>
