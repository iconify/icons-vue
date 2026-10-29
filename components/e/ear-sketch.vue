<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p7i0qepff.css';
import '../../css/z/zkeo5mycj.css';
import '../../css/s/sa4mc4iol.css';
import '../../css/i/it_2xjlfu.css';
import '../../css/e/e9lwaol1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p7i0qepff"/><path class="wm-k zkeo5mycj"/><path class="sa4mc4iol wm-a"/><path class="it_2xjlfu wm-k"/><path class="e9lwaol1z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ear-sketch" /></template>
