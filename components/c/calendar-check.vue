<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xck5rbc3z.css';
import '../../css/g/g70z56b6i.css';
import '../../css/w/wqj33hb5g.css';
import '../../css/z/zggadzblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="g70z56b6i"/><path class="wqj33hb5g"/><path class="zggadzblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calendar-check" /></template>
