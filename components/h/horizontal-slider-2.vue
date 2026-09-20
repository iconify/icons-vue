<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmfebc3mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmfebc3mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:horizontal-slider-2" /></template>
