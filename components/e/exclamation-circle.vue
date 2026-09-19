<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/utt4feufe.css';
import '../../css/q/qzf3wxbei.css';
import '../../css/w/wqaq_tblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="utt4feufe"/><circle class="qzf3wxbei"/><path clip-rule="evenodd" class="wqaq_tblz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:exclamation-circle" /></template>
