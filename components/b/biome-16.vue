<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyc5w-_2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gyc5w-_2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:biome-16" /></template>
