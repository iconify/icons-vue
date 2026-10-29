<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/mx878-b0u.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/g/gmt-k0r6b.css';
import '../../css/p/pzj6afbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="mx878-b0u wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="gmt-k0r6b wm-k"/><path class="pzj6afbau wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cpu-blueprint" /></template>
