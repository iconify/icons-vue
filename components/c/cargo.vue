<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iitrv6b_u.css';
import '../../css/j/jeqnyebai.css';
import '../../css/p/pzp-sptxq.css';
import '../../css/r/r-n3tp3un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="iitrv6b_u"><path class="jeqnyebai"/><path class="pzp-sptxq"/><path class="r-n3tp3un"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cargo" /></template>
