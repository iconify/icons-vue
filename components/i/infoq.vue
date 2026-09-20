<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf-fpf_ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf-fpf_ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:infoq" /></template>
