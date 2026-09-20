<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty8jntqqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty8jntqqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dash" /></template>
