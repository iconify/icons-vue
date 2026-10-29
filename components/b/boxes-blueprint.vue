<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fj4kk9bgl.css';
import '../../css/y/yonu32bng.css';
import '../../css/p/pd8ob3bre.css';
import '../../css/s/shg57gb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fj4kk9bgl wm-deco"/><path class="wm-deco yonu32bng"/><path class="pd8ob3bre wm-k"/><path class="shg57gb1y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:boxes-blueprint" /></template>
