<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy05w96zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy05w96zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:garuda-linux" /></template>
