<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wjnap5mog.css';
import '../../css/u/uazu3ybua.css';
import '../../css/b/bxma9mfut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wjnap5mog"/><path class="uazu3ybua"/><path class="bxma9mfut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:clipboard-pen" /></template>
