<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lgfg79rry.css';
import '../../css/y/y6gza9ttc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lgfg79rry"/><path class="y6gza9ttc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:globe" /></template>
