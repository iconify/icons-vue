<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o11i93z8m.css';
import '../../css/x/xtw1k2b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o11i93z8m"/><path class="xtw1k2b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:conflux" /></template>
