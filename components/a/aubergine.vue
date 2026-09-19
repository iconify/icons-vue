<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-roltbpz.css';
import '../../css/t/thf8vdb1b.css';
import '../../css/o/oxcajzmoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-roltbpz"/><path class="thf8vdb1b"/><path class="oxcajzmoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:aubergine" /></template>
