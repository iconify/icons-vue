<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-khqclun.css';
import '../../css/l/lt58dk2xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z-khqclun"/><path class="lt58dk2xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-panel-20" /></template>
