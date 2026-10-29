<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/u7d2hzbvv.css';
import '../../css/b/bxjv56brc.css';
import '../../css/b/bkfqcl9lq.css';
import '../../css/l/lrg-fdc4r.css';
import '../../css/m/m0xe8rb-t.css';
import '../../css/u/uqhmd6bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="u7d2hzbvv wm-deco"/><path class="bxjv56brc wm-deco"/><path class="bkfqcl9lq wm-k"/><path class="lrg-fdc4r wm-a"/><path class="m0xe8rb-t wm-k"/><path class="uqhmd6bht wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-line-blueprint" /></template>
