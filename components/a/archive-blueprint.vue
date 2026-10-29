<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/aa_t0xbkv.css';
import '../../css/e/e-xr1cc5b.css';
import '../../css/n/nge5cfbll.css';
import '../../css/o/ok8irzbkw.css';
import '../../css/o/oy6a688zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="aa_t0xbkv wm-deco"/><path class="e-xr1cc5b wm-deco"/><path class="nge5cfbll wm-deco"/><path class="ok8irzbkw wm-k"/><path class="oy6a688zn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:archive-blueprint" /></template>
