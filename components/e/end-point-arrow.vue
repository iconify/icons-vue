<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjnuvtb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjnuvtb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:end-point-arrow" /></template>
