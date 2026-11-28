<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqch5x_ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqch5x_ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:book-open-heart" /></template>
