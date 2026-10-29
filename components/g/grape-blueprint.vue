<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bbfu44bql.css';
import '../../css/j/jk7r1z21b.css';
import '../../css/e/enkc8mbld.css';
import '../../css/r/rmi2m3b9i.css';
import '../../css/l/lssc9-1xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bbfu44bql wm-deco"/><path class="jk7r1z21b wm-deco"/><path class="enkc8mbld wm-deco"/><path class="rmi2m3b9i wm-k"/><path class="lssc9-1xp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grape-blueprint" /></template>
