<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dissgdc8k.css';
import '../../css/l/l2mdcy6pi.css';
import '../../css/y/yi1ay4bjk.css';
import '../../css/o/o6fimhbzm.css';
import '../../css/a/ad9j6bb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="dissgdc8k"/><path class="l2mdcy6pi"/><path class="yi1ay4bjk"/><path class="o6fimhbzm"/><path class="ad9j6bb8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:garage" /></template>
