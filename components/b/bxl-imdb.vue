<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rllujjb-s.css';
import '../../css/n/n36fbt-7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rllujjb-s"/><path class="n36fbt-7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-imdb" /></template>
