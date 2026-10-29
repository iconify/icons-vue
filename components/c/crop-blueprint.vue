<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p9qcgac9q.css';
import '../../css/u/uuupksbft.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/i/i6x7mbc2d.css';
import '../../css/a/agyau5bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p9qcgac9q wm-deco"/><path class="uuupksbft wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="i6x7mbc2d"/><path class="agyau5bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crop-blueprint" /></template>
