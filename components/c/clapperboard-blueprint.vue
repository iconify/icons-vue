<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/t/tpx8s4b7z.css';
import '../../css/z/zevicpjgz.css';
import '../../css/t/to5bdybou.css';
import '../../css/k/kuknt1bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="tpx8s4b7z wm-deco"/><path class="wm-deco zevicpjgz"/><path class="to5bdybou"/><path class="kuknt1bgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clapperboard-blueprint" /></template>
