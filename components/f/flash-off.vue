<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjygdv48g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjygdv48g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:flash-off" /></template>
