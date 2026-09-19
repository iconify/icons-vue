<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r1_1lvbhw.css';
import '../../css/n/nccjn1-dm.css';
import '../../css/i/ioeyefb3u.css';
import '../../css/w/wq06lglvi.css';
import '../../css/o/ouv6_cpwo.css';
import '../../css/t/t1qniluor.css';
import '../../css/g/ghmz_bb0v.css';
import '../../css/u/uz9ibwvwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><g transform="translate(3 3)"><path class="r1_1lvbhw"/><ellipse class="nccjn1-dm"/><path class="ioeyefb3u"/></g><path class="wq06lglvi"/><ellipse class="ouv6_cpwo"/><path class="t1qniluor"/><path class="ghmz_bb0v"/><path class="uz9ibwvwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:disc-play" /></template>
