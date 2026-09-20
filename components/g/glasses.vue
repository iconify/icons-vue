<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymix36bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymix36bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:glasses" /></template>
