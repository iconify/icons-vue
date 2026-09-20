<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1d2yybis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1d2yybis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-netflix" /></template>
