<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bnef_pb8w.css';
import '../../css/n/n2wyxqbbe.css';
import '../../css/f/f6r1adbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="bnef_pb8w"/><path class="n2wyxqbbe"/><path class="f6r1adbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cake-slice" /></template>
