<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcl3y6bkj.css';
import '../../css/p/plthgm9xi.css';
import '../../css/z/zn72xdbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcl3y6bkj"/><path class="plthgm9xi"/><path class="zn72xdbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-today" /></template>
