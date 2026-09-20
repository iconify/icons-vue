<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p81p5o69s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p81p5o69s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lore-epic-games" /></template>
