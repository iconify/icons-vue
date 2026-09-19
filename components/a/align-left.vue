<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx8y2ds-k.css';
import '../../css/m/mwfiol2dj.css';
import '../../css/r/rwc7d5bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="mwfiol2dj"/><path class="rwc7d5bjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:align-left" /></template>
