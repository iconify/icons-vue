<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/l3jgcybau.css';
import '../../css/n/nbj7ro57z.css';
import '../../css/k/kjq20lbyg.css';
import '../../css/h/h2our83dc.css';
import '../../css/x/xdwdw1wlj.css';
import '../../css/s/snig7ubjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="l3jgcybau wm-deco"/><path class="nbj7ro57z wm-deco"/><path class="kjq20lbyg wm-k"/><path class="h2our83dc wm-a"/><path class="wm-k xdwdw1wlj"/><path class="snig7ubjb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-down-to-line-blueprint" /></template>
