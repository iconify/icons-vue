<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pie-r5bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pie-r5bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:codepen-fill" /></template>
