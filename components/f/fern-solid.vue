<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmp5x_b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmp5x_b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fern-solid" /></template>
