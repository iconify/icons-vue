<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw-q3pb-z.css';
import '../../css/u/utb2ysxhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cw-q3pb-z"/><path class="utb2ysxhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:glasses" /></template>
