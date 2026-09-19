<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hri_yxbcb.css';
import '../../css/n/noyl5dl3k.css';
import '../../css/c/c4nv1ybwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hri_yxbcb"/><path clip-rule="evenodd" class="noyl5dl3k"/><path class="c4nv1ybwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bandage-adhesive2x-outline" /></template>
