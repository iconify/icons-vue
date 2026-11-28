<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z90ezch_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z90ezch_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:castle-star" /></template>
