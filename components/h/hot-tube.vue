<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g7k409bhs.css';
import '../../css/n/nqbip7m1a.css';
import '../../css/h/hbl-7rbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g7k409bhs"/><path class="nqbip7m1a"/><path class="hbl-7rbdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hot-tube" /></template>
