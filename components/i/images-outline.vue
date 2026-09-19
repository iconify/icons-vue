<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyadontyn.css';
import '../../css/z/z8rxepbkv.css';
import '../../css/k/kgn0a9bzn.css';
import '../../css/p/ppvvrsbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zyadontyn"/><rect class="z8rxepbkv"/><ellipse class="kgn0a9bzn"/><path class="ppvvrsbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:images-outline" /></template>
