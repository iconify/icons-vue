<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iuwgo5_3k.css';
import '../../css/o/oo4oedcbq.css';
import '../../css/z/zbpan-bvy.css';
import '../../css/y/yebcb12-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iuwgo5_3k"/><path class="oo4oedcbq"/><path class="zbpan-bvy"/><path class="yebcb12-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-wave-line-duotone" /></template>
