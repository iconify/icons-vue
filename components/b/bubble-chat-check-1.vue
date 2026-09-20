<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3xtuk_0z.css';
import '../../css/g/gt0t_gfvc.css';
import '../../css/n/ni1x5_bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="gt0t_gfvc"/><path class="ni1x5_bad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:bubble-chat-check-1" /></template>
