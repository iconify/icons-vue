<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/ms0gcnb0v.css';
import '../../css/n/ni8xmk99j.css';
import '../../css/z/zt6ewu8gv.css';
import '../../css/q/qqiubgb1z.css';
import '../../css/z/zt1e34j_a.css';
import '../../css/o/o5bvdq2hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ms0gcnb0v"/><path class="ni8xmk99j"/><path class="zt6ewu8gv"/><path class="qqiubgb1z"/><path class="zt1e34j_a"/><path class="o5bvdq2hn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-hearts-outline" /></template>
