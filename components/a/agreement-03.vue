<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bqqlflk3u.css';
import '../../css/z/zw9ur85fx.css';
import '../../css/t/tlhsqgbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bqqlflk3u"/><path class="zw9ur85fx"/><path class="tlhsqgbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:agreement-03" /></template>
