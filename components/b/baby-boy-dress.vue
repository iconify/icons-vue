<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/ys_zhewgg.css';
import '../../css/j/jcat81bta.css';
import '../../css/x/xmh7xxbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ys_zhewgg"/><path class="jcat81bta"/><path class="xmh7xxbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:baby-boy-dress" /></template>
