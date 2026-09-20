<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf-m56b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uf-m56b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calendar-star-remix" /></template>
