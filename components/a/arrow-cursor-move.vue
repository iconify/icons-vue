<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv73z5bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv73z5bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-cursor-move" /></template>
