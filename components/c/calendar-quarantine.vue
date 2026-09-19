<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yy7a_jbhx.css';
import '../../css/j/j2onbccwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="yy7a_jbhx"/><path clip-rule="evenodd" class="j2onbccwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:calendar-quarantine" /></template>
