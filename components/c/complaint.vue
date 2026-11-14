<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/oagawgbbv.css';
import '../../css/w/wbdy8gb0y.css';
import '../../css/k/k4xam1b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oagawgbbv"/><path class="wbdy8gb0y"/><path class="k4xam1b7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:complaint" /></template>
