<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yw3kbde_g.css';
import '../../css/i/icn76kbna.css';
import '../../css/k/khzkibcfv.css';
import '../../css/g/g69ez5b_t.css';
import '../../css/x/xbty9ccox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yw3kbde_g"/><path class="icn76kbna"/><path class="khzkibcfv"/><path class="g69ez5b_t"/><path class="xbty9ccox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:email-action-remove" /></template>
