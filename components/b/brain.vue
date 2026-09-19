<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rijwomp7z.css';
import '../../css/x/xn8-eabzo.css';
import '../../css/a/anodm08oq.css';
import '../../css/a/acnb4lb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rijwomp7z"/><path class="xn8-eabzo"/><path clip-rule="evenodd" class="anodm08oq"/><path class="acnb4lb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:brain" /></template>
