<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqm3hwbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqm3hwbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hard-hat" /></template>
