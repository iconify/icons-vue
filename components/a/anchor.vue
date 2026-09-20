<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pt93twbsc.css';
import '../../css/w/wv5f_1brg.css';
import '../../css/d/dsp6khz0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pt93twbsc"/><circle class="wv5f_1brg"/><path class="dsp6khz0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:anchor" /></template>
