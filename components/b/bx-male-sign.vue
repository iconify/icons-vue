<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij52glb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij52glb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-male-sign" /></template>
