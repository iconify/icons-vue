<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/mfl50s7ox.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/l/l1zsq4jxr.css';
import '../../css/m/mxrtyruna.css';
import '../../css/u/uflkzv69y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="mfl50s7ox wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="l1zsq4jxr wm-k"/><path class="mxrtyruna wm-a"/><path class="uflkzv69y wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fingerprint-blueprint" /></template>
