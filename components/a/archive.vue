<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/l/l_jvi_-3i.css';
import '../../css/y/yclr26l0t.css';
import '../../css/t/tovsduesy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="l_jvi_-3i"/><path class="yclr26l0t"/><path class="tovsduesy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:archive" /></template>
