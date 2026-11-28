<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhvdx6bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhvdx6bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cast-x" /></template>
