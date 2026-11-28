<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iivyk3ixn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k4-c7ob6h.css';
import '../../css/w/w7_mhrwuu.css';
import '../../css/h/h84pf6b7c.css';
import '../../css/c/cjqev4bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iivyk3ixn secondary"/><g class="dt0cm9dhy primary"><path class="k4-c7ob6h"/><path class="w7_mhrwuu"/><path class="h84pf6b7c"/><path class="cjqev4bed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:calendar-user-duo" /></template>
