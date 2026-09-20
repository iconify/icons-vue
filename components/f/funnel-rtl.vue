<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul9m5ac3g.css';
import '../../css/j/j26snyixz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ul9m5ac3g"/><path class="j26snyixz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:funnel-rtl" /></template>
