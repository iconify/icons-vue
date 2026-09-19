<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ntgb1z6op.css';
import '../../css/c/c1j-6_1tm.css';
import '../../css/j/j2dz0wb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ntgb1z6op"/><path clip-rule="evenodd" class="c1j-6_1tm"/><path clip-rule="evenodd" class="j2dz0wb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lungs" /></template>
