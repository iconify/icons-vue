<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo1x5-bwi.css';
import '../../css/h/hf6tzubxh.css';
import '../../css/q/qe32f93df.css';
import '../../css/l/ly0fd4b1i.css';
import '../../css/l/lyfl-t8ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo1x5-bwi"/><path clip-rule="evenodd" class="hf6tzubxh"/><g clip-rule="evenodd" class="qe32f93df"><path class="ly0fd4b1i"/><path class="lyfl-t8ti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycling-round-bold-duotone" /></template>
