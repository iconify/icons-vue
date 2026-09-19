<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h39n9xbvk.css';
import '../../css/h/hz82di4ei.css';
import '../../css/b/b5r2-9b9m.css';
import '../../css/i/i2uebbkhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="h39n9xbvk"/><rect class="hz82di4ei"/><rect class="b5r2-9b9m"/><rect class="i2uebbkhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ellipsis-circle-bold" /></template>
