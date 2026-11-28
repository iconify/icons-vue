<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx65m281l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx65m281l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:headphones-heart" /></template>
