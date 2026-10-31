<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms0at3b6u.css';
import '../../css/q/q-kryjbiy.css';
import '../../css/d/dx89yjc2p.css';
import '../../css/a/as-9dnbxr.css';
import '../../css/x/xr3toxb2s.css';
import '../../css/c/c4h3gzb8x.css';
import '../../css/d/dxtq256oj.css';
import '../../css/z/zmg14pbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ms0at3b6u"/><path class="q-kryjbiy"/><path class="dx89yjc2p"/><path class="as-9dnbxr"/><path class="xr3toxb2s"/><path class="c4h3gzb8x"/><path class="dxtq256oj"/><path class="zmg14pbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:bacon" /></template>
