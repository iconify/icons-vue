<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mok_4qi5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mok_4qi5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-filter-round" /></template>
