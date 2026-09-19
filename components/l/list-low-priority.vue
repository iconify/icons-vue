<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi0f-zb-z.css';
import '../../css/j/jvrj_gb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hi0f-zb-z"/><path class="jvrj_gb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:list-low-priority" /></template>
