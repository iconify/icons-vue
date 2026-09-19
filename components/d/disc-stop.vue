<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/znkfbeihh.css';
import '../../css/n/nccjn1-dm.css';
import '../../css/i/ioeyefb3u.css';
import '../../css/a/ah8imtbda.css';
import '../../css/y/y626a9bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><g transform="translate(3 3)"><path class="znkfbeihh"/><ellipse class="nccjn1-dm"/><path class="ioeyefb3u"/></g><path class="ah8imtbda"/><path class="y626a9bts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:disc-stop" /></template>
