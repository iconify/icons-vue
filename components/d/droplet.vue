<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/ryeh_ibvu.css';
import '../../css/j/jlt6l4bhy.css';
import '../../css/l/ldb6sabpz.css';
import '../../css/b/bnmq8ssqv.css';
import '../../css/i/iyeuvgq7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ryeh_ibvu wm-k"/><path class="jlt6l4bhy wm-k"/><path class="ldb6sabpz wm-k"/><path class="bnmq8ssqv wm-shine"/><path class="iyeuvgq7f wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:droplet" /></template>
