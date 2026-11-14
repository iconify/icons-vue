<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kgpwylbgu.css';
import '../../css/i/i7dhmn0vg.css';
import '../../css/o/of67m-bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kgpwylbgu"/><path class="i7dhmn0vg"/><path class="of67m-bqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-rose" /></template>
