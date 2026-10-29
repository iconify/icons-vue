<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pof-48b5b.css';
import '../../css/j/je9239bfw.css';
import '../../css/t/t-nw4xpov.css';
import '../../css/m/mtrv0mdwe.css';
import '../../css/b/bipz22vit.css';
import '../../css/m/mf5ziac3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pof-48b5b"/><path class="je9239bfw wm-k"/><path class="t-nw4xpov wm-k"/><path class="mtrv0mdwe wm-k"/><path class="bipz22vit wm-a"/><path class="mf5ziac3q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dental-chair-sketch" /></template>
