<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2r1s-rsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2r1s-rsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cursor-target-1-bold" /></template>
