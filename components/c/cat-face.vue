<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbu9iw12k.css';
import '../../css/w/w1rz5ibpm.css';
import '../../css/f/ftm_wspzc.css';
import '../../css/l/l4y59e4oe.css';
import '../../css/y/yp9zh8bzh.css';
import '../../css/p/pdam7cclh.css';
import '../../css/r/rwzblo3wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="pbu9iw12k"/><path class="w1rz5ibpm"/><ellipse class="ftm_wspzc"/><ellipse class="l4y59e4oe"/><path class="yp9zh8bzh"/><path class="pdam7cclh"/><path class="rwzblo3wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cat-face" /></template>
