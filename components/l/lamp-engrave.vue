<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/unez3en8j.css';
import '../../css/n/nvv_c9j-h.css';
import '../../css/a/anw3ijuct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="unez3en8j"/><path class="nvv_c9j-h wm-shadow"/><path class="anw3ijuct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lamp-engrave" /></template>
