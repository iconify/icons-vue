<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sicp8y6ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sicp8y6ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bohemiainteractive" /></template>
