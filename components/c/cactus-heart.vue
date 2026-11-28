<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_didac0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_didac0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cactus-heart" /></template>
