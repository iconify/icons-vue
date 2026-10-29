<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jxzikob-p.css';
import '../../css/n/nup2x6b3k.css';
import '../../css/k/k8e5r6sft.css';
import '../../css/b/b5bfvoblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jxzikob-p"/><path class="nup2x6b3k wm-shadow"/><path class="k8e5r6sft"/><path class="b5bfvoblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crop-engrave" /></template>
