<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrs790btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrs790btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dashboard-gear" /></template>
