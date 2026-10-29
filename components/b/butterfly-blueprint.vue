<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gxg59svjo.css';
import '../../css/b/b5d9gkptz.css';
import '../../css/r/r1kpz-btk.css';
import '../../css/w/wqky-ncod.css';
import '../../css/r/r87huipyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gxg59svjo wm-deco"/><path class="b5d9gkptz wm-deco"/><path class="r1kpz-btk wm-deco"/><path class="wqky-ncod"/><path class="r87huipyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:butterfly-blueprint" /></template>
