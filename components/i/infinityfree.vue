<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj1t25d3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj1t25d3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:infinityfree" /></template>
