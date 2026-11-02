<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruo8un5iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruo8un5iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-chevron-up-line" /></template>
