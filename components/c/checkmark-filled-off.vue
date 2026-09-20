<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yh-bcbcdd.css';
import '../../css/x/x5q-macsu.css';
import '../../css/f/fk592nv7k.css';
import '../../css/a/a1tx6bc4w.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yh-bcbcdd"/><path clip-rule="evenodd" class="x5q-macsu"/><path clip-rule="evenodd" class="fk592nv7k"/><path clip-rule="evenodd" class="a1tx6bc4w"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:checkmark-filled-off" /></template>
