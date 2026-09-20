<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um9xjdh3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um9xjdh3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-arrow-left" /></template>
