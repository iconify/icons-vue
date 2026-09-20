<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k92n8qzdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k92n8qzdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:beanie-remix" /></template>
