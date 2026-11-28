<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shrrvucug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shrrvucug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bag-heart" /></template>
