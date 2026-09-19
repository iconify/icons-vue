<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t2k-17biz.css';
import '../../css/c/czp-3jxtt.css';
import '../../css/g/gdryfccos.css';
import '../../css/o/oxtw1expr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="t2k-17biz"/><path clip-rule="evenodd" class="czp-3jxtt"/><path clip-rule="evenodd" class="gdryfccos"/><path class="oxtw1expr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:eyeglasses-outline" /></template>
