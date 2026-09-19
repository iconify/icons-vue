<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2pty-1kt.css';
import '../../css/c/cad1wdxuy.css';
import '../../css/n/n1y99614y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2pty-1kt"/><path class="cad1wdxuy"/><path class="n1y99614y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-menu" /></template>
