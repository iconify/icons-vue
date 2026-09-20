<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq3hkcbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq3hkcbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:grids" /></template>
