<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg1--abbd.css';
import '../../css/z/zudizmbbe.css';
import '../../css/w/w9b1o0b9t.css';
import '../../css/a/a5k16ccib.css';
import '../../css/p/pxav1kb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="dg1--abbd"/><circle class="zudizmbbe"/><circle class="w9b1o0b9t"/><path class="a5k16ccib"/><path class="pxav1kb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-backup" /></template>
