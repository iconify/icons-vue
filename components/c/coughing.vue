<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/za70xkulc.css';
import '../../css/z/zj82fgh6g.css';
import '../../css/j/jfsc1ebhd.css';
import '../../css/h/ho_kgdb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="za70xkulc"/><path clip-rule="evenodd" class="zj82fgh6g"/><path class="jfsc1ebhd"/><path clip-rule="evenodd" class="ho_kgdb6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:coughing" /></template>
