<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/as6_xp3_v.css';
import '../../css/m/mxvtch9hs.css';
import '../../css/e/ec91lg3uo.css';
import '../../css/c/c66wu4b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="as6_xp3_v"/><path class="mxvtch9hs"/><path class="ec91lg3uo"/><path class="c66wu4b9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:globe-bold-duotone" /></template>
