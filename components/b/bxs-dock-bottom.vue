<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flvfd689n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flvfd689n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dock-bottom" /></template>
