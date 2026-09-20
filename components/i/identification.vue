<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xedjwxbpm.css';
import '../../css/c/c3j04fb6w.css';
import '../../css/z/zgj-9nbrm.css';
import '../../css/g/g3vy2_9sr.css';
import '../../css/x/xun5vn6pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xedjwxbpm"/><path clip-rule="evenodd" class="c3j04fb6w"/><path clip-rule="evenodd" class="zgj-9nbrm"/><path class="g3vy2_9sr"/><path class="xun5vn6pg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:identification" /></template>
