<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i623bfbsp.css';
import '../../css/v/veyji9_1k.css';
import '../../css/d/dm587nnti.css';
import '../../css/y/ymmq4nbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i623bfbsp"/><path class="veyji9_1k"/><path class="dm587nnti"/><path class="ymmq4nbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:arduino" /></template>
