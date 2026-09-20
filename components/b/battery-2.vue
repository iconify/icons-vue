<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgmfl_7bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgmfl_7bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-2" /></template>
