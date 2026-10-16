<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1zbnl2gi.css';
import '../../css/u/u_65e3bqj.css';
import '../../css/l/ld-zmgngl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c1zbnl2gi"/><path class="u_65e3bqj"/><path class="ld-zmgngl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earthing-switch-48-bold" /></template>
