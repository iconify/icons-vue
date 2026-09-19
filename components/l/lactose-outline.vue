<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yili_cwtj.css';
import '../../css/i/im8__db2r.css';
import '../../css/j/j6489r_4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yili_cwtj"/><path clip-rule="evenodd" class="im8__db2r"/><path class="j6489r_4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lactose-outline" /></template>
