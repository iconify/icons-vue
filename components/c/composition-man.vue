<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oto60ts8x.css';
import '../../css/b/bo7oo35sp.css';
import '../../css/r/r_1ey_bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oto60ts8x"/><path class="bo7oo35sp"/><path class="r_1ey_bjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:composition-man" /></template>
