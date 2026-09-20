<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya2ssjs1d.css';
import '../../css/y/yxk_uibgr.css';
import '../../css/q/qxtj0v7jh.css';
import '../../css/w/w72lbhmvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ya2ssjs1d"/><path class="yxk_uibgr"/><path class="qxtj0v7jh"/><path class="w72lbhmvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:folding-hand-fan" /></template>
