<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfj_ec0cs.css';
import '../../css/j/jz2nnzb1g.css';
import '../../css/p/puzcifo1g.css';
import '../../css/z/zzrsoebtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfj_ec0cs"/><path class="jz2nnzb1g"/><path class="puzcifo1g"/><path class="zzrsoebtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-loop" /></template>
