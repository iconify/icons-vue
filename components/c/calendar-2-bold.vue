<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acz22eljo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acz22eljo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-2-bold" /></template>
