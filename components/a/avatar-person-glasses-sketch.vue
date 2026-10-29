<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hm2vo1b0z.css';
import '../../css/t/tbdw6sa0q.css';
import '../../css/y/yfdct_b5e.css';
import '../../css/a/avxkvvbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hm2vo1b0z wm-k"/><path class="tbdw6sa0q wm-k"/><path class="wm-k yfdct_b5e"/><path class="avxkvvbkc wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-person-glasses-sketch" /></template>
