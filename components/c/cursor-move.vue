<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbmrg5bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbmrg5bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cursor-move" /></template>
