<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_nyb7jhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_nyb7jhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-1-line" /></template>
