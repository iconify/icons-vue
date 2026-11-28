<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojee99y2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojee99y2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:aperture" /></template>
