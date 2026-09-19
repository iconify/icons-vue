<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfs41yb4d.css';
import '../../css/a/a9y45tbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfs41yb4d"/><path class="a9y45tbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bookmark-heart" /></template>
