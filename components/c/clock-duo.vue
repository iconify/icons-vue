<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjzczbv1j.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/riz3hy1-t.css';
import '../../css/j/jriq20k1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjzczbv1j secondary"/><g class="dt0cm9dhy primary"><circle class="riz3hy1-t"/><path class="jriq20k1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clock-duo" /></template>
