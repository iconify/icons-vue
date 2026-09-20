<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/psv_8pbss.css';
import '../../css/j/jfo40lxqz.css';
import '../../css/x/xhnnlxbog.css';
import '../../css/u/uzry01bej.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="psv_8pbss"/><path class="jfo40lxqz"/><path clip-rule="evenodd" class="xhnnlxbog"/><path clip-rule="evenodd" class="uzry01bej"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:database-circle" /></template>
