<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/m8t98nbfb.css';
import '../../css/f/f0mlzybpd.css';
import '../../css/r/rxzaf1bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m8t98nbfb"/><rect class="f0mlzybpd"/><rect class="rxzaf1bym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-column-stacked" /></template>
