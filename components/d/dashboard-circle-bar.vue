<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/c/c9ns0wb1n.css';
import '../../css/m/mnw43chky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="c9ns0wb1n"/><path class="mnw43chky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-circle-bar" /></template>
