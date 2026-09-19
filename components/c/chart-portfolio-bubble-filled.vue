<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhn4pvblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xhn4pvblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-portfolio-bubble-filled" /></template>
