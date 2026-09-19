<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b-ej1f0ud.css';
import '../../css/m/m24p57kbj.css';
import '../../css/i/il4xqrbrm.css';
import '../../css/c/cs2xpclua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b-ej1f0ud"/><path clip-rule="evenodd" class="m24p57kbj"/><path class="il4xqrbrm"/><path clip-rule="evenodd" class="cs2xpclua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-charge-outline" /></template>
