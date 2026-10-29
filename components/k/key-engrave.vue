<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kqeyp4k-t.css';
import '../../css/c/cbqvu9b5z.css';
import '../../css/x/xpmjmd9yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kqeyp4k-t"/><path class="cbqvu9b5z wm-shadow"/><path class="xpmjmd9yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key-engrave" /></template>
