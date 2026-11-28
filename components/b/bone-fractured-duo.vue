<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn0-deb2k.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/el1390byg.css';
import '../../css/e/ehrxwkb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn0-deb2k secondary"/><g class="dt0cm9dhy primary"><path class="el1390byg"/><path class="ehrxwkb6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bone-fractured-duo" /></template>
