<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yq4w0ibij.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/x/xtdeyac8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yq4w0ibij"/><path class="o7-ag87sb wm-deco"/><path class="xtdeyac8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:globe-blueprint" /></template>
