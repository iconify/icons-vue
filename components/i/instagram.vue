<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g8dfhpbfn.css';
import '../../css/x/x89edcbli.css';
import '../../css/g/gjxb9oblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g8dfhpbfn"/><path class="x89edcbli"/><path clip-rule="evenodd" class="gjxb9oblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:instagram" /></template>
