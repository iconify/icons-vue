<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cjnwjzb4c.css';
import '../../css/z/zir5_7bld.css';
import '../../css/g/gygffl34c.css';
import '../../css/h/hu5w36xiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cjnwjzb4c"/><path clip-rule="evenodd" class="zir5_7bld"/><path clip-rule="evenodd" class="gygffl34c"/><path clip-rule="evenodd" class="hu5w36xiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:headphones-square-sound-bold" /></template>
