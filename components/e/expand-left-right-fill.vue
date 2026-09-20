<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvlda4jhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvlda4jhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-left-right-fill" /></template>
