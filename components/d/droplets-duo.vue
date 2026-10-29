<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mv82wccyp.css';
import '../../css/f/f72f_rjii.css';
import '../../css/u/urb3kpbld.css';
import '../../css/i/idk2wtbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mv82wccyp"/><path class="f72f_rjii wm-a"/><path class="urb3kpbld"/><path class="idk2wtbbi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:droplets-duo" /></template>
