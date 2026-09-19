<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo-j068ov.css';
import '../../css/c/cujh-cb3j.css';
import '../../css/z/zj9g_cb3z.css';
import '../../css/q/qi6-mdk2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uo-j068ov"/><path class="cujh-cb3j"/><path class="zj9g_cb3z"/><path class="qi6-mdk2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:airplane" /></template>
