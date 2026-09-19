<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wh2onkwsw.css';
import '../../css/j/jb--wo5yd.css';
import '../../css/d/dhk2nbc2r.css';
import '../../css/z/zs7twcstk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wh2onkwsw"/><path clip-rule="evenodd" class="jb--wo5yd"/><path class="dhk2nbc2r"/><path clip-rule="evenodd" class="zs7twcstk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cell-nuclei" /></template>
