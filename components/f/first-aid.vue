<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vhklpmewb.css';
import '../../css/y/y1-snpblu.css';
import '../../css/t/t1pug1bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vhklpmewb"/><path class="y1-snpblu"/><path class="t1pug1bay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:first-aid" /></template>
