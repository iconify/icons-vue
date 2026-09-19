<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/age6e0b3t.css';
import '../../css/n/nccjn1-dm.css';
import '../../css/i/ioeyefb3u.css';
import '../../css/l/liwnglp2l.css';
import '../../css/c/cr2woabks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><g transform="translate(3 3)"><path class="age6e0b3t"/><ellipse class="nccjn1-dm"/><path class="ioeyefb3u"/></g><path class="liwnglp2l"/><path class="cr2woabks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:disc-pause" /></template>
