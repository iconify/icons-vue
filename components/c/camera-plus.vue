<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3igl-bgw.css';
import '../../css/t/taswdu53c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3igl-bgw"/><path class="taswdu53c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:camera-plus" /></template>
