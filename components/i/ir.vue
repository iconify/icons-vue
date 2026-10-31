<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sqf6xz70z.css';
import '../../css/l/l27639bbw.css';
import '../../css/q/qgedusuli.css';
import '../../css/c/c29hiodty.css';
import '../../css/m/m6nlbsbsd.css';
import '../../css/b/ba-8qqbfp.css';
import '../../css/j/j3riuj0hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":173};
const content = `<g class="bi12bsetm"><path class="sqf6xz70z"/><path class="l27639bbw"/><path class="qgedusuli"/><path class="c29hiodty"/><path class="m6nlbsbsd"/><path class="ba-8qqbfp"/><path class="j3riuj0hp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:ir" /></template>
