<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xm1lv7b-r.css';
import '../../css/e/e8p--9_xn.css';
import '../../css/i/ik7gh80-w.css';
import '../../css/p/pu01xn-qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xm1lv7b-r"/><path class="e8p--9_xn"/><path class="ik7gh80-w"/><path class="pu01xn-qp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:link-1-outline" /></template>
