<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl_o3vrxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_o3vrxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fishing-rod" /></template>
