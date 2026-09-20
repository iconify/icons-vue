<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7-g_bb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7-g_bb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-minus-2" /></template>
