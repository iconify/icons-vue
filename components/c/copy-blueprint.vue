<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/cjgkwhwya.css';
import '../../css/b/bw_7xbbfl.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/b/bpxha0pxg.css';
import '../../css/b/b5x9xi0bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="cjgkwhwya wm-deco"/><path class="bw_7xbbfl wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="bpxha0pxg wm-k"/><path class="b5x9xi0bu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:copy-blueprint" /></template>
