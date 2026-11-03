<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rjl-osbit.css';
import '../../css/f/feh9g0bqf.css';
import '../../css/j/jmd8w56ud.css';
import '../../css/g/gvcn7xpex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjl-osbit"/><rect class="feh9g0bqf"/><rect class="jmd8w56ud"/><rect class="gvcn7xpex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:diagram-flow-horizontal" /></template>
