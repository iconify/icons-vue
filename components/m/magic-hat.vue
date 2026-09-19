<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/r8g3kubio.css';
import '../../css/b/b-b-8eb2h.css';
import '../../css/x/xsvqqibcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="r8g3kubio"/><path class="b-b-8eb2h"/><ellipse class="xsvqqibcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:magic-hat" /></template>
