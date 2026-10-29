<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/aq69r9byh.css';
import '../../css/l/lvx6itxnk.css';
import '../../css/x/xupe0ib4r.css';
import '../../css/w/wfsha8jvf.css';
import '../../css/d/domdhwbzo.css';
import '../../css/b/b86m5ybhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="aq69r9byh wm-deco"/><path class="lvx6itxnk wm-deco"/><path class="wm-deco xupe0ib4r"/><path class="wfsha8jvf wm-k"/><path class="domdhwbzo wm-a"/><path class="b86m5ybhz wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:carrot-blueprint" /></template>
