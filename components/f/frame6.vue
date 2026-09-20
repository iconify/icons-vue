<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipvtvf6ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipvtvf6ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:frame6" /></template>
