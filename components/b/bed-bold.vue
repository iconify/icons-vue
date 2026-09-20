<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zi1833bza.css';
import '../../css/k/kt_9h6beg.css';
import '../../css/t/t9n961ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zi1833bza"/><path class="kt_9h6beg"/><path clip-rule="evenodd" class="t9n961ban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bed-bold" /></template>
