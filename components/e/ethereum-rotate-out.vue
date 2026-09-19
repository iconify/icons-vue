<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pao9cab5l.css';
import '../../css/u/uuj-dyb-z.css';
import '../../css/j/j4om64bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pao9cab5l"/><path class="uuj-dyb-z"/><path class="j4om64bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ethereum-rotate-out" /></template>
