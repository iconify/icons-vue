<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz32_dk2s.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tnzxd8b-c.css';
import '../../css/t/twb1ymtuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz32_dk2s secondary"/><g class="dt0cm9dhy primary"><path class="tnzxd8b-c"/><path class="twb1ymtuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:droplet-half-duo" /></template>
