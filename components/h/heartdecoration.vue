<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c__7q5bmw.css';
import '../../css/r/rknde7bur.css';
import '../../css/m/mst02g6_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c__7q5bmw"/><path class="rknde7bur"/><path class="mst02g6_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heartdecoration" /></template>
