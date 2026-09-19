<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c-wokwols.css';
import '../../css/d/dtid9hb3k.css';
import '../../css/z/zd5iasbeb.css';
import '../../css/y/yz1mcrb9n.css';
import '../../css/t/t9tj1bctq.css';
import '../../css/q/qv7vcda1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="c-wokwols"/><path class="dtid9hb3k"/><path class="zd5iasbeb"/><path class="yz1mcrb9n"/><path class="t9tj1bctq"/><path class="qv7vcda1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:compass-1-outline" /></template>
