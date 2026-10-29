<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f1b9shfss.css';
import '../../css/z/zomf0k0wi.css';
import '../../css/l/l94wqzpmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f1b9shfss wm-k"/><path class="wm-k zomf0k0wi"/><path class="l94wqzpmb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-checks-sketch" /></template>
