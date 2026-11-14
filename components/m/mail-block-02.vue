<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c9ult2btp.css';
import '../../css/q/qdzi_jzoh.css';
import '../../css/g/ggell_ipy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c9ult2btp"/><path class="qdzi_jzoh"/><path class="ggell_ipy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-block-02" /></template>
