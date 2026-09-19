<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhodxcc8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhodxcc8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-back-thick" /></template>
