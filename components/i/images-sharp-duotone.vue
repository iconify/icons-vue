<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/xtbju33sf.css';
import '../../css/z/z308c8bnb.css';
import '../../css/n/ne_lywboa.css';
import '../../css/y/y-gfmr48b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xtbju33sf"/><path class="z308c8bnb"/><path class="ne_lywboa"/><path class="y-gfmr48b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images-sharp-duotone" /></template>
