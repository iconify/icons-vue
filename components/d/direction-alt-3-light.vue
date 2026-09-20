<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/b/b3tg1bi3m.css';
import '../../css/h/hwwubw2ud.css';
import '../../css/o/o6g7n3blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="b3tg1bi3m"/><path class="hwwubw2ud"/><path class="o6g7n3blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:direction-alt-3-light" /></template>
