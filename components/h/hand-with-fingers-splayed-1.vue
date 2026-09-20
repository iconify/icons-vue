<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zymf_u6-e.css';
import '../../css/d/dfb_70snl.css';
import '../../css/p/p1y1we2cu.css';
import '../../css/u/ujbdo19su.css';
import '../../css/u/uymgdabjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zymf_u6-e"/><path class="dfb_70snl"/><path class="p1y1we2cu"/><path class="ujbdo19su"/><path class="uymgdabjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:hand-with-fingers-splayed-1" /></template>
