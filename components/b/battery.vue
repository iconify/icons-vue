<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xwhj4xbwf.css';
import '../../css/p/pbc518b4s.css';
import '../../css/a/a72a8abyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="xwhj4xbwf"/><path class="pbc518b4s"/><path clip-rule="evenodd" class="a72a8abyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:battery" /></template>
