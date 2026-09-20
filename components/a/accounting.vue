<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb1hd8b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="wb1hd8b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:accounting" /></template>
