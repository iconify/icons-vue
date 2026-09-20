<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_jp68bwx.css';
import '../../css/u/ui8pwhfnc.css';
import '../../css/i/i392j1bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l_jp68bwx"/><path class="ui8pwhfnc"/><path class="i392j1bbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-filled" /></template>
