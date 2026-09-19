<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3ivccum.css';
import '../../css/g/g3bzu6tbx.css';
import '../../css/w/wwarg-bxz.css';
import '../../css/f/fm1umgbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="g3bzu6tbx"/><path class="wwarg-bxz"/><path class="fm1umgbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:add-print" /></template>
