<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_x11l5zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_x11l5zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:exit-fullscreen-square-filled" /></template>
