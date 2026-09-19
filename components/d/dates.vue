<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bwlz-_lem.css';
import '../../css/t/t2mokvbsr.css';
import '../../css/n/ninu6dbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bwlz-_lem"/><path class="t2mokvbsr"/><path class="ninu6dbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dates" /></template>
