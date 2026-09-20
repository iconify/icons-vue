<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/e7lqm9obr.css';
import '../../css/z/z37i7yg4n.css';
import '../../css/n/n724o7bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e7lqm9obr"/><path clip-rule="evenodd" class="z37i7yg4n"/><path class="n724o7bcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cable-sharp-duotone" /></template>
