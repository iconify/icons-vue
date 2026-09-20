<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mkih2u7bz.css';
import '../../css/e/eydo_ywvt.css';
import '../../css/n/nvhzykbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mkih2u7bz"/><path clip-rule="evenodd" class="eydo_ywvt"/><path clip-rule="evenodd" class="nvhzykbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cycling-duotone" /></template>
