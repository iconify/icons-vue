<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mwz9-fkga.css';
import '../../css/n/nba_jbchp.css';
import '../../css/t/t-bfk7ioi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="mwz9-fkga"/><path class="nba_jbchp"/><path class="t-bfk7ioi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:database-export" /></template>
