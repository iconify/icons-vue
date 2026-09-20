<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7v3kjbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7v3kjbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:kitchenware-spatula-1-bold" /></template>
