<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/htb413hay.css';
import '../../css/b/b1e4swiah.css';
import '../../css/x/xwj6wumfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="htb413hay"/><path class="b1e4swiah"/><path class="xwj6wumfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar2-event" /></template>
