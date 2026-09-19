<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/prmuj21_q.css';
import '../../css/l/lpl4xulxg.css';
import '../../css/y/yf6f28u9n.css';
import '../../css/f/f1go28opi.css';
import '../../css/h/h--a0vv5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="prmuj21_q"/><path clip-rule="evenodd" class="lpl4xulxg"/><path clip-rule="evenodd" class="yf6f28u9n"/><path class="f1go28opi"/><path class="h--a0vv5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:bluetooth-print" /></template>
