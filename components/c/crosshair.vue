<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih1th_vdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih1th_vdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:crosshair" /></template>
