<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mju4wgbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mju4wgbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coffee" /></template>
