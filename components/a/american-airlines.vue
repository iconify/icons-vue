<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdcv578kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdcv578kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:american-airlines" /></template>
