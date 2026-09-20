<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwkhe_-2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwkhe_-2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:add-column" /></template>
