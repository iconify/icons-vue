<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/v6lu6-pan.css';
import '../../css/k/k5raeubzg.css';
import '../../css/l/lfzj22qgn.css';
import '../../css/j/jy3c7oi9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="v6lu6-pan wm-deco"/><path class="k5raeubzg wm-deco"/><path class="lfzj22qgn wm-k"/><path class="jy3c7oi9w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:banknote-blueprint" /></template>
