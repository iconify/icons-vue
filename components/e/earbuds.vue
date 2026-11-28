<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmju0pblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmju0pblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:earbuds" /></template>
