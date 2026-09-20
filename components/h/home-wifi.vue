<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f-3v2ab3t.css';
import '../../css/l/lkf3u0e1e.css';
import '../../css/e/ewmg-bcus.css';
import '../../css/a/ad8mu8bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f-3v2ab3t"/><path class="lkf3u0e1e"/><path class="ewmg-bcus"/><path clip-rule="evenodd" class="ad8mu8bes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-wifi" /></template>
