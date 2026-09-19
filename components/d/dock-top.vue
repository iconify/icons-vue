<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdfr1w_pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdfr1w_pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dock-top" /></template>
