<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vzo3ypbps.css';
import '../../css/x/x43s2zn6y.css';
import '../../css/p/pfllnjb4h.css';
import '../../css/a/aw4h_vb6l.css';
import '../../css/z/zbfd7gbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="vzo3ypbps"/><path class="x43s2zn6y"/><path class="pfllnjb4h"/><path class="aw4h_vb6l"/><path class="zbfd7gbum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-pause-linear" /></template>
