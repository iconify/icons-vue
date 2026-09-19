<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7zc2dxoc.css';
import '../../css/m/m_1_1mbyc.css';
import '../../css/h/hq39p8b-u.css';
import '../../css/b/b9gxndrtw.css';
import '../../css/c/c8zi06iay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="a7zc2dxoc"/><path class="m_1_1mbyc"/><path class="hq39p8b-u"/><path class="b9gxndrtw"/><path class="c8zi06iay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:foxheart" /></template>
