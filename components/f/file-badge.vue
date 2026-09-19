<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bybr2q82h.css';
import '../../css/t/t34te5bfi.css';
import '../../css/g/gw45uub7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bybr2q82h"/><path class="t34te5bfi"/><path class="gw45uub7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-badge" /></template>
