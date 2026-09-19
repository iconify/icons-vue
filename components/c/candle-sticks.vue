<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9l5qacpy.css';
import '../../css/t/t4a3_jblt.css';
import '../../css/y/ypjfbwbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9l5qacpy"/><path class="t4a3_jblt"/><path class="ypjfbwbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:candle-sticks" /></template>
