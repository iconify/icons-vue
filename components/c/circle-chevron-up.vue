<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f31j-cpil.css';
import '../../css/g/grw0dgbik.css';
import '../../css/o/oajhruw5p.css';
import '../../css/r/rjg00-qxz.css';
import '../../css/o/opc2jpbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f31j-cpil wm-k"/><path class="grw0dgbik wm-k"/><path class="oajhruw5p wm-k"/><path class="rjg00-qxz wm-shine"/><path class="opc2jpbwk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:circle-chevron-up" /></template>
