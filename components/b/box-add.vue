<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/az8dcqgmq.css';
import '../../css/g/gcwqm4-4k.css';
import '../../css/x/xgtgfnecr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="az8dcqgmq"/><path class="gcwqm4-4k"/><path class="xgtgfnecr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box-add" /></template>
