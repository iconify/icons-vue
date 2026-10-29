<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p2zebubvw.css';
import '../../css/a/ad70xqb6p.css';
import '../../css/w/w7c9ezsct.css';
import '../../css/g/g-df8cc8q.css';
import '../../css/b/bx-9x2f1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p2zebubvw wm-k"/><path class="ad70xqb6p wm-a"/><path class="w7c9ezsct wm-shadow"/><path class="g-df8cc8q wm-k"/><path class="bx-9x2f1z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:indian-rupee-engrave" /></template>
