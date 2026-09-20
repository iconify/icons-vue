<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utv3gdowh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utv3gdowh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:car-tool-jumper-cables-bold" /></template>
