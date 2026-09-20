<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a_p7us8mf.css';
import '../../css/s/ss28ywb2k.css';
import '../../css/p/pmzs0tmcf.css';
import '../../css/b/bov2ir9ks.css';
import '../../css/e/e2m-l-b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a_p7us8mf"/><path class="ss28ywb2k"/><path class="pmzs0tmcf"/><path clip-rule="evenodd" class="bov2ir9ks"/><path clip-rule="evenodd" class="e2m-l-b1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:gift" /></template>
