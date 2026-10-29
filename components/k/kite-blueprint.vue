<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/y4pkjtbjs.css';
import '../../css/i/ibpnj1b4u.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/j/jlv0b8x4n.css';
import '../../css/w/wod2x8bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco y4pkjtbjs"/><path class="ibpnj1b4u wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="jlv0b8x4n"/><path class="wod2x8bdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kite-blueprint" /></template>
