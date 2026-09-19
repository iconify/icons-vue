<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ono2lmbnf.css';
import '../../css/z/zphoc6n5m.css';
import '../../css/w/wsjjh00ev.css';
import '../../css/r/rsbqj3bbt.css';
import '../../css/l/lgi36gbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ono2lmbnf"/><path clip-rule="evenodd" class="zphoc6n5m"/><path class="wsjjh00ev"/><path class="rsbqj3bbt"/><path class="lgi36gbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:book-atlas" /></template>
