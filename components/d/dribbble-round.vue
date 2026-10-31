<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpsy1qb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpsy1qb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dribbble-round" /></template>
