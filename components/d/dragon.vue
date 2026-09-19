<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/punmc35bv.css';
import '../../css/x/xwh7pzbbi.css';
import '../../css/x/xjz3x4bzs.css';
import '../../css/a/au9b4g8cs.css';
import '../../css/n/nrqnj2blu.css';
import '../../css/h/h-iagik0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="punmc35bv"/><path class="xwh7pzbbi"/><path class="xjz3x4bzs"/><path class="au9b4g8cs"/><path class="nrqnj2blu"/><path class="h-iagik0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:dragon" /></template>
