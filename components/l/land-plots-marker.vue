<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n20_8lkzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n20_8lkzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:land-plots-marker" /></template>
