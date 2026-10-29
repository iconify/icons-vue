<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/rwl7u5b9f.css';
import '../../css/w/wvzx3gczq.css';
import '../../css/n/nge5cfbll.css';
import '../../css/p/pyewu0dff.css';
import '../../css/q/qbc871vgt.css';
import '../../css/p/pfp6hfb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="rwl7u5b9f wm-deco"/><path class="wm-deco wvzx3gczq"/><path class="nge5cfbll wm-deco"/><path class="pyewu0dff wm-k"/><path class="qbc871vgt wm-a"/><path class="pfp6hfb3z wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-monster-blueprint" /></template>
