<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6t7335sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6t7335sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-heart" /></template>
