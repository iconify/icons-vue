<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv9tauant.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv9tauant"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:contract-clock" /></template>
