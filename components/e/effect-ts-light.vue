<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9n_9-b9e.css';
import '../../css/z/zhvmu9b_u.css';
import '../../css/o/osur64b6w.css';
import '../../css/w/w195kz00o.css';
import '../../css/y/yuhbhbg-h.css';
import '../../css/r/roombi3ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":220,"height":220};
const content = `<g class="u9n_9-b9e"><path clip-rule="evenodd" class="zhvmu9b_u"/><path clip-rule="evenodd" class="osur64b6w"/><path clip-rule="evenodd" class="w195kz00o"/><path class="yuhbhbg-h"/><path clip-rule="evenodd" class="roombi3ku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:effect-ts-light" /></template>
