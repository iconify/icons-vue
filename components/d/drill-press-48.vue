<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1fw4u24k.css';
import '../../css/a/ayk1lqtqi.css';
import '../../css/q/qbjntbton.css';
import '../../css/u/uzx1cpbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x1fw4u24k"/><path class="ayk1lqtqi"/><path class="qbjntbton"/><path class="uzx1cpbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drill-press-48" /></template>
