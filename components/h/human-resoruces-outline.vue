<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v_78o9bzj.css';
import '../../css/r/rf89yab9s.css';
import '../../css/j/jzyc6ac6r.css';
import '../../css/w/wqfwsubtj.css';
import '../../css/o/o163b2bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="v_78o9bzj"/><path class="rf89yab9s"/><path clip-rule="evenodd" class="jzyc6ac6r"/><path class="wqfwsubtj"/><path clip-rule="evenodd" class="o163b2bww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:human-resoruces-outline" /></template>
