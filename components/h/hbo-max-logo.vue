<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/l7u-4rb7i.css';
import '../../css/a/ah92i4n0h.css';
import '../../css/d/di3s11blc.css';
import '../../css/m/mu62w5buf.css';
import '../../css/q/qd8-7pq5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="l7u-4rb7i"/><path class="ah92i4n0h"/><path class="di3s11blc"/><path class="mu62w5buf"/><path class="qd8-7pq5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:hbo-max-logo" /></template>
