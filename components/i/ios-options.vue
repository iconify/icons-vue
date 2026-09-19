<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts2-1lbsz.css';
import '../../css/n/nv41fibrk.css';
import '../../css/q/qz6wmnbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ts2-1lbsz"/><path class="nv41fibrk"/><path class="qz6wmnbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-options" /></template>
