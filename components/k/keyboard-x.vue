<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyogb06xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyogb06xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:keyboard-x" /></template>
