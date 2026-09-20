<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgslyd9sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xgslyd9sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:cursor-speed-1" /></template>
