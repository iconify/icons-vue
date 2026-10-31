<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hf5yhlbua.css';
import '../../css/e/eu2bpjbbr.css';
import '../../css/z/zkic90lmy.css';
import '../../css/y/ygwioac4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hf5yhlbua wm-k"/><path class="eu2bpjbbr wm-deco"/><path class="wm-k zkic90lmy"/><path class="wm-shadow ygwioac4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:euro" /></template>
