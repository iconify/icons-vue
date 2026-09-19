<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5cg8fb9r.css';
import '../../css/d/dj7oebbfk.css';
import '../../css/r/rg511obvo.css';
import '../../css/t/t0v4pnbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="dj7oebbfk"/><path class="rg511obvo"/><path class="t0v4pnbgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:balance" /></template>
