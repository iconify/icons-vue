<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgm50yc_s.css';
import '../../css/r/rjvu1wn-k.css';
import '../../css/n/nbudjgbrb.css';
import '../../css/g/gecge6__a.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/m/m4-6vibjc.css';
import '../../css/p/pb83nccyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zgm50yc_s"/><path class="rjvu1wn-k"/><path class="nbudjgbrb"/><path class="gecge6__a"/><g class="jn8qy4bru"><path class="m4-6vibjc"/><path class="pb83nccyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dagger" /></template>
