<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9--i9bid.css';
import '../../css/j/jillytggr.css';
import '../../css/f/fcvnsw9zt.css';
import '../../css/i/i-otnfmzx.css';
import '../../css/a/ajh8fsxju.css';
import '../../css/n/n_fv7b7om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9--i9bid"/><path class="jillytggr"/><path class="fcvnsw9zt"/><path class="i-otnfmzx"/><path class="ajh8fsxju"/><path class="n_fv7b7om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ace-stream" /></template>
