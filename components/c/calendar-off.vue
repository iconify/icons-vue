<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f589aobdb.css';
import '../../css/i/i278szqpx.css';
import '../../css/y/y-0yi6qaz.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f589aobdb"/><path clip-rule="evenodd" class="i278szqpx"/><path class="y-0yi6qaz"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:calendar-off" /></template>
