<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akv7glb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akv7glb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-microchip" /></template>
