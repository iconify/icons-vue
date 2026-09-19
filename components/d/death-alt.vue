<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m058yjboy.css';
import '../../css/l/lpf31_i2c.css';
import '../../css/e/e7ui7sb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m058yjboy"/><path class="lpf31_i2c"/><path clip-rule="evenodd" class="e7ui7sb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:death-alt" /></template>
