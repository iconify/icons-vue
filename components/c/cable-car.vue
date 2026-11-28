<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9hiye1kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9hiye1kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cable-car" /></template>
