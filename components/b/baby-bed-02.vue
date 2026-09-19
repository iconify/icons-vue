<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/ryzs-efko.css';
import '../../css/v/vm6i8hwdu.css';
import '../../css/w/w276c4mco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ryzs-efko"/><path class="vm6i8hwdu"/><path class="w276c4mco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:baby-bed-02" /></template>
