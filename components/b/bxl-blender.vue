<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvqpbpbpk.css';
import '../../css/g/gpfbyab6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvqpbpbpk"/><path class="gpfbyab6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-blender" /></template>
