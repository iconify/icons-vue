<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny_2a6iec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny_2a6iec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-zoom-in" /></template>
