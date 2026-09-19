<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yv5n49_tc.css';
import '../../css/g/gud1rsb6l.css';
import '../../css/m/mpznc0bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yv5n49_tc"/><path class="gud1rsb6l"/><path class="mpznc0bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bitcoin-bag" /></template>
