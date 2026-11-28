<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iug3obbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iug3obbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gauge-solid" /></template>
