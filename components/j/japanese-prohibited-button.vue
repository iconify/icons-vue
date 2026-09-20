<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlbqo2bly.css';
import '../../css/c/c13pizxnv.css';
import '../../css/z/zmuow6bjd.css';
import '../../css/u/ue06dqb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" transform="matrix(.2612 0 0 .2621 -91.39 -3.483)" class="wlbqo2bly"/><path class="c13pizxnv"/><path transform="matrix(.2612 0 0 .2621 -91.39 -3.483)" class="zmuow6bjd"/><path transform="matrix(.2612 0 0 .262 -91.386 -3.483)" class="ue06dqb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:japanese-prohibited-button" /></template>
