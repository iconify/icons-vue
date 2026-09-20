<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/gcwqm4-4k.css';
import '../../css/x/xgtgfnecr.css';
import '../../css/i/iqja8bcqa.css';
import '../../css/v/vbslnbc8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcwqm4-4k"/><path class="xgtgfnecr"/><path class="iqja8bcqa"/><path class="vbslnbc8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box-time" /></template>
