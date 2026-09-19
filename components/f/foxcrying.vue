<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7zc2dxoc.css';
import '../../css/m/m_1_1mbyc.css';
import '../../css/o/of8gbk85h.css';
import '../../css/p/pfj8ubzfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="a7zc2dxoc"/><path class="m_1_1mbyc"/><path class="of8gbk85h"/><path class="pfj8ubzfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:foxcrying" /></template>
