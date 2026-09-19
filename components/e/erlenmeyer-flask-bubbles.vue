<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz8smpd4d.css';
import '../../css/r/r0711mb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mz8smpd4d"/><path class="r0711mb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:erlenmeyer-flask-bubbles" /></template>
