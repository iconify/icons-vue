<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lmki3ubtm.css';
import '../../css/q/qtikdbcvk.css';
import '../../css/s/sfcunzbzv.css';
import '../../css/w/w8i_ob5hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<g class="ft5dv1b6b"><path class="lmki3ubtm"/><path class="qtikdbcvk"/><path class="sfcunzbzv"/><path class="w8i_ob5hf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:better-auth-light" /></template>
