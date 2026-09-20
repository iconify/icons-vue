<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g--ezebfp.css';
import '../../css/a/a8qr8zbfl.css';
import '../../css/d/d8kbcbc-x.css';
import '../../css/a/ad35ldbxn.css';
import '../../css/l/l8hihu8ge.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g--ezebfp"/><path class="a8qr8zbfl"/><path class="d8kbcbc-x"/><path class="ad35ldbxn"/><path class="l8hihu8ge"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:lesbian" /></template>
