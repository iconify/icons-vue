<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyzc91b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyzc91b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:line-arrow-triangle-loop-remix" /></template>
