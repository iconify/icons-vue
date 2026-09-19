<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjt-f13vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjt-f13vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-1-thin" /></template>
