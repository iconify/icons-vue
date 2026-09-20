<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2xv61bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2xv61bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-alt-circle-down-solid" /></template>
