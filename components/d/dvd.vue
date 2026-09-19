<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p5bichbdj.css';
import '../../css/l/lt7-bebau.css';
import '../../css/x/xi61yebtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p5bichbdj"/><path class="lt7-bebau"/><path class="xi61yebtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:dvd" /></template>
