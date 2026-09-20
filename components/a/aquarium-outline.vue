<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-x6lpj1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-x6lpj1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:aquarium-outline" /></template>
