<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3wtdab_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i3wtdab_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-down-left-stipple-inner" /></template>
